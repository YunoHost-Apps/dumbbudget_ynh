<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# DumbBudget pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/dumbbudget)](https://ci-apps.yunohost.org/ci/apps/dumbbudget/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/dumbbudget)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/dumbbudget)

[![Installer DumbBudget avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbbudget)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer DumbBudget rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Une application simple et sécurisée de gestion de budget personnel avec protection par code PIN. Suivez vos revenus et vos dépenses grâce à une interface propre et moderne.

### Caractéristiques

- Accès protégé par un code PIN
- Suivi des revenus et des dépenses
- Calcul du solde en temps réel
- Catégorisation des transactions
- Filtrage par plage de dates
- Tri par date ou par montant
- Conception réactive
- Thème clair/foncé
- Exportation au format CSV
- Filtrer les transactions par type
- Prise en charge de plusieurs devises
    

**Version incluse :** 1.0.0~ynh2

## Captures d’écran

![Capture d’écran de DumbBudget](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.dumbware.io/>
- Dépôt de code officiel de l’app : <https://github.com/DumbWareio/DumbBudget>
- YunoHost Store : <https://apps.yunohost.org/app/dumbbudget>
- Signaler un bug : <https://github.com/YunoHost-Apps/dumbbudget_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/dumbbudget_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbbudget_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dumbbudget -u https://github.com/YunoHost-Apps/dumbbudget_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
