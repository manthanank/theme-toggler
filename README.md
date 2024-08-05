# Theme Toggler

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.1.0.

## Project Structure

```text
theme-toggler/
├── public/
│   |── favicon.ico
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── theme-toggler/
│   │   │   │   ├── theme-toggler.component.html
│   │   │   │   ├── theme-toggler.component.ts
│   │   │   │   ├── theme-toggler.component.scss
│   │   │   │   └── theme-toggler.component.spec.ts
│   │   ├── services/
│   │   │   └── theme.service.ts
│   │   ├── shared/
│   │   │   ├── navbar/
│   │   │   │   ├── navbar.component.html
│   │   │   │   ├── navbar.component.ts
│   │   │   │   ├── navbar.component.scss
│   │   │   │   └── navbar.component.spec.ts
│   │   ├── app.component.html
│   │   └── app.component.ts
|   |   └── app.component.scss
|   |   └── app.config.ts
|   |   └── app.routes.ts
│   ├── index.html
│   ├── main.ts
│   └── styles.scss
├── .editorconfig
├── .gitignore
├── angular.json
├── package.json
├── package-lock.json
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.spec.json
├── tailwind.config.js
└── README.md
```

## Functionality

The ThemeToggler application allows users to switch between light and dark themes. The application includes the following components and services:

- **ThemeToggler**: Toggle button that allows users to switch between light and dark themes. The button is displayed in the navbar component.
- **ThemeService**: This service manages the current theme state and provides methods to switch themes. It uses local storage to persist the user's theme preference across sessions.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
