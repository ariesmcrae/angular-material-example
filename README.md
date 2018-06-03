# AngularMaterialExample

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.7.

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

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

# Example Angular-CLI commands:
#### Create new project
`ng new angular-material-example --style=scss`

#### Create new module
`ng g m shared/material --flat --dry-run`
```
CREATE src/app/shared/material.module.spec.ts (291 bytes)
CREATE src/app/shared/material.module.ts (192 bytes)
```
#### Run server and open app in browser
`ng s -o` 
Runs the server and opens up the browser.

#### Create another module with routing
`ng g m demo --routing --dry-run`
```
CREATE src/app/demo/demo-routing.module.ts (247 bytes)
CREATE src/app/demo/demo.module.spec.ts (259 bytes)
CREATE src/app/demo/demo.module.ts (271 bytes)
```

#### Generate a component
`ng g c demo/buttons --no-spec --inline-style --inline-template --dry-run`
```
CREATE src/app/demo/buttons/buttons.component.ts (259 bytes)
UPDATE src/app/demo/demo.module.ts (351 bytes)
```