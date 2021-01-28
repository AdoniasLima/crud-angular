<p align="center"><img width="130" src="https://angular.io/assets/images/logos/angular/angular.svg"/></p>

  
Crud application developed in angular and a simple back-end in json-server.

#### What did I learn from developing this application?

- Framework structure;
- Components;
- Modules;
- Observables;
- Pipes;
- Directives;
- Services.

## Requirements

- Node version 12.18.4 or lasted
- Npm version 6.14.6 or lasted

## Installation
    command: npm install (All folders, back-end and front-end)

## Routes

#### Angular
|            URL    |Method|Description|
|----------------|-------------------------------|-----------------------------|
|/|GET|Home page.|
|/products|GET|All products page.|
|/products/create|GET|Create product page.|

#### Json-server
|            URL    |Method|Description|
|----------------|-------------------------------|-----------------------------|
|/products|GET|All products|
|/products|POST|{name: "name_product", price: 123.45}|
|/products|PUT|{id: id_number, name: "name_product", price: 123.45}|
|/products/create|DELETE|{id: id_number}|

## Important Angular Commands
    command: ng new name_your_project --minimal
    command: ng add @angular/material
    command: ng ng g c components/template/header
    command: ng ng g d directives/gray