# MyApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

## Development server

Run `ng serve --open` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


## App File Structure

The app lives in the src folder. All Angular components, templates, styles, images, and anything else your app needs go here. Any files outside of this folder are meant to support building your app.

```
src
  app
    app.component.css
    app.component.html
    app.component.spec.ts
    app.component.ts
    app.module.ts
  assets
    .gitkeep
  environments
    environment.prod.ts
    environment.ts
  browserslist
  favicon.ico
  index.html
  karma.conf.js
  main.ts
  polyfills.ts
  styles.css
  test.ts
  tsconfig.app.json
  tsconfig.spec.json
  tslint.json
  ```

## App Features

This basic app has many of the features you'd expect to find in a data-driven application. It acquires and displays a list of users, edits a selected user's detail, and navigates among different views of user data.

It was built using:

1. Use built-in Angular directives to show and hide elements and display lists of user data.
2. Create Angular components to display user details and show an array of users.
3. Use one-way data binding for read-only data.
4. Add editable fields to update a model with two-way data binding.
5. Bind component methods to user events, like keystrokes and clicks.
6. Enable users to select a user from a master list and edit that user in the details view.
7. Format data with pipes.
8. Create a shared service to assemble the users.
9. Use routing to navigate among different views and their components.