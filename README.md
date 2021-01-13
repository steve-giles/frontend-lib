# FrontendLib

This project libraray contains Angular Custom Elements for managing functionality within HomeCEU.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

- Run `npm run build:dts`
- Copy `\elements\frontend-lib.js` and `\dist\frontend-lib\styles.css` to the Server where the element is exposed.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Regession tests make use of [Cucumber with Cypress](https://www.npmjs.com/package/cypress-cucumber-preprocessor).

- `npm run test:cypress:ci` to run regression tests locally -  starts the application, waits for the URL, then runs regression tests; when the tests end, shuts down app
- `npm run test:cypress:run` to run regression tests locally against the currently running application

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
