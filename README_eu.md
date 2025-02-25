<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# DumbBudget YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/dumbbudget)](https://ci-apps.yunohost.org/ci/apps/dumbbudget/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/dumbbudget)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/dumbbudget)

[![Instalatu DumbBudget YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbbudget)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek DumbBudget YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A simple, secure personal budgeting app with PIN protection. Track your income and expenses with a clean, modern interface.

### Features

- PIN-protected access
- Track income and expenses
- Real-time balance calculations
- Categorize transactions
- Date range filtering
- Sort by date or amount
- Responsive design
- Light/Dark theme
- Export to CSV
- Filter transactions by type
- Multi-currency support


**Paketatutako bertsioa:** 1.0.0~ynh1

## Pantaila-argazkiak

![DumbBudget(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.dumbware.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/DumbWareio/DumbBudget>
- YunoHost Denda: <https://apps.yunohost.org/app/dumbbudget>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/dumbbudget_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/dumbbudget_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbbudget_ynh/tree/testing --debug
edo
sudo yunohost app upgrade dumbbudget -u https://github.com/YunoHost-Apps/dumbbudget_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
