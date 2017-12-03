# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


*************************************************************************************
Historique des commandes utiles

Creer une application
  
    ng new angular-tour-of-heroes //créer un sous repertoire

Démarrer l'application
  
    ng serve --open   //permet de lancer d'ouvrir une fenetre dans le navigateur.

creation d'un composant
  
    ng generate component heroes  //creation d'un component dans un sous repertoire "heroes"
    ng generate component hero-detail //idem

Creation d'un service
    ng generate service hero

    ng generate service message --module=app
      //The --module=app option tells the CLI to provide this service in the AppModule

Creation d'un module pour le routing
    
    ng generate module app-routing --flat --module=app

Generation du livrable
    
    ng build

  Copier du repertoire ./dist dans la web app dans .\src\main\resources\static
  puis builder normalement l'appli (ex. spring boot)
