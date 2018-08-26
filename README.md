# Example of PWA (Progressive web application)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

After generating basic project structure with "ng new app-example" command, use the following command to add PWA stuff:

Run `ng add @angular/pwa` command

Also don't forger to use real application server (like http-server from npm) to test PWA features.

Run `ng build --prod` command will create minimal sources for production app in `dist` folder.

Then go the `dist/app` folder and run the following command:

Run `http-server -o` command to deploy app on the localhost

Now you can enjoy PWA features

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
