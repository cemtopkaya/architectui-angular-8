# architectui-angular-8
ArchitectUI tasarımının angular 8 e göre güncellenmiş hali. https://github.com/DashboardPack/architectui-angular-theme-free Adresindeki sürüm angular 7 ye göreydi.

## Değişimler

En son halinde chartjs sorunu yüzünden açılış sayfasını değiştirdim. Fırsat bulursam chart için uyumlu bir bileşeni entegre edeceğim.

```
      // {path: '', component: AnalyticsComponent, data: {extraParameter: 'dashboardsMenu'}},
      {path: '',  redirectTo: '/elements/buttons-standard', pathMatch: 'full'},
```      

ng2-charts ile chart.js paketlerinin kurulumunun sıralaması önemli https://stackoverflow.com/a/59639386/104085 adresindeki gibi önce ng2-charts sonra chart.js kurulunca sorun kalmıyor.


