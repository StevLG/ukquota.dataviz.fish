# SakanaApi (en test)

travail à faire :

- responsive (remplacer les média queries par des classes bootstrap)

- layout de la page à revoir (bordures, disposition du texte...)

- ergonomie de la partie formulaire / graphique à revoir (ajout d'une modale ?)


Dernières modifications :

-- Commit 17 (04/08/2019) :  Ajout d'une carte interactive avec la librairie Leaflet.js


fait :

    premier nettoyage du code
    validation du formulaire d'interrogation des données
    affichage des données choisies sous forme graphique (bar et linecharts)
    affichage des données sous forme de tableau filtrable avec le module Ag-Grid
    les autres champs à ajouter (+ calendrier pour date, avec le module Material Angular également)
    intégration d'un champs Select 'name_specie' avec liste des noms qui marche / module 'material' pour angular(données réelles)
    ajout d'un système d'onglets (tabs de Material Angular)

à faire :

    champs 'super-zone' à ajouter: nécessaire ???

    problème avec l'affichage dans le champs date d'une plage de date (format = anglais) > à revoir, si possible...

    modifications :

-- commit 10 :

Travail en cours : création d'un formulaire d'interrogation des données sur un graphique de la librairie 'chart.js' (type 'linechart')

Modification de CSS (header...)

Suppression de 'quickstart-2.1.js non fonctionnel dans ce module. Le retrouver ici : https://github.com/DarKaweit/Node-Extract_SQL-Insert

-- Commit 9 :

Ajout de html, de CSS et possibilité d'affichage de tableaux et de graphiques (design en travail) sur des données extraites d'une BDD MySQL

-- Commit 8 :

Ajout du module 'quickstart-2.1.js de récupérations de données sélectionnées d'une pièce-jointe de mail au format '.xlsx', de leur parsage en fichier '.csv' (qui seront enregistrés dans le dossier 'Tableaux') et l'intégration de données selectionnées en Base de donnée MySQL (fichier : 'datafishuk-3.0.sql'). Ce module est intégré à partir de https://github.com/DarKaweit/Node-Extract_SQL-Insert (à consulter pour plus de détails)

-- Commit 7 :

Possibilité d'interroger une BDD Mysql et de répondre les données sur un tableau Possibilité d'interroger une BDD Mysql et de répondre les données d'un objet 'json' sur un graphique (Attention : pour l'instant, au choix : l'abscisse ou l'ordonnée)
Data fishing platform project 

by Code.bzh.

With Angular, ChartJS, Express, Sequelize, MySQL, and Api Gmail

Run `npm run build` to run the app

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.7. 

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
