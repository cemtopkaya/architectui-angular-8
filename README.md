# architectui-angular-8
ArchitectUI tasarımının angular 8 e göre güncellenmiş hali. https://github.com/DashboardPack/architectui-angular-theme-free Adresindeki sürüm angular 7 ye göreydi.

## Değişimler
En son halinde chartjs sorunu yüzünden açılış sayfasını değiştirdim. Fırsat bulursam chart için uyumlu bir bileşeni entegre edeceğim.

      // {path: '', component: AnalyticsComponent, data: {extraParameter: 'dashboardsMenu'}},
      {path: '',  redirectTo: '/elements/buttons-standard', pathMatch: 'full'},

ng2-charts ile chart.js paketlerinin kurulumunun sıralaması önemli https://stackoverflow.com/a/59639386/104085 adresindeki gibi önce ng2-charts sonra chart.js kurulunca sorun kalmıyor.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.26.

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
