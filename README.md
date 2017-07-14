# MathsQuiz

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


## Report on work experience

During the course of a week in july, i have programmed, tested and overall developed a program to test primary school students on random mathematics questions,s orted into easy, medium and hard. This was done as a semi-team project with my work experience collegue where we planned/designed together but ultimately developed the project seperately. The quiz generates 20 random mathematics questions (difficulty based on their chosen difficulty). The user then has to answer these questions consecutively before the timer has counted to 2 minutes. The teacher can control the contenet of the difficulties (addition,subtraction,division and mulitplication) either from a firebase database(currently implemented) which will update the difficulties globally or through the in built teacher interface which will update the difficulties locally only.

## Trying it yourself

If you would like to have a go at duplicating this for yourself, you would need to be in posession of the following:

*Gitbash (or an alternative git client)
*Node.JS (with firebase and angular2 installed)
*Atom IDE
*Access to googles firebase service (specifically their database and hosting services)

## Getting started
In order to get started you need to install all the requirements through Node.js by running the following commands:
*`npm install -g @angular/cli`
*`npm install -g firebase-tools`
You then need to start a project by opening Git Bash(or chosen git client) and running `ng new "insert project name here"` to start a new app with angular. When you have went through that process you should run the app in development mode by using the command: `ng serve`. This means that any progress you make on the project can be shown at `localhost:4200` which you can just view in your web browser. To make progress just edit the files within the file `<InsertProjectNameHere/src/app/` using the Atom IDE

## Deploying to firebase
After you have done all previous steps, you can deploy the application to firebases hosting system which wioll allow you to access the apps user interface from anywhere with an internet connection. It is completely safe and the spark package is absolutely free. 
Firstly, make an account on firebase(should just be able to use any google account you may already have).
Secondly, login to your firebase account through Git Bash by using command `firebase login` where you should be promted to enter your logn details.
Once logged in, use `firebase init` to initialise the project followed by `ng build` to generate a dist folder. 
Finally deploy your app using `firebase deploy`.

