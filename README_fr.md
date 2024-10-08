<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Stirling PDF pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/stirling.svg)](https://ci-apps.yunohost.org/ci/apps/stirling/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/stirling.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/stirling.maintain.svg)

[![Installer Stirling PDF avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Stirling PDF rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Il s'agit d'un outil de manipulation de PDF robuste, hébergé localement et basé sur le Web, utilisant Docker. Il vous permet d'effectuer diverses opérations sur des fichiers PDF, notamment le fractionnement, la fusion, la conversion, la réorganisation, l'ajout d'images, la rotation, la compression, etc. Cette application Web hébergée localement a évolué pour englober un ensemble complet de fonctionnalités, répondant à toutes vos exigences PDF.

Stirling PDF n'initie aucun appel sortant à des fins de tenue de registres ou de suivi.

Tous les fichiers et PDF existent soit exclusivement côté client, résident dans la mémoire du serveur uniquement pendant l'exécution de la tâche, soit résident temporairement dans un fichier uniquement pour l'exécution de la tâche. Tout fichier téléchargé par l'utilisateur aura été supprimé du serveur à ce stade.

**Version incluse :** 0.29.0~ynh1

**Démo :** <https://stirlingpdf.io/>

## Captures d’écran

![Capture d’écran de Stirling PDF](./doc/screenshots/screenshot.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://www.stirlingpdf.com/>
- Documentation officielle utilisateur : <https://docs.stirlingpdf.com/>
- Documentation officielle de l’admin : <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Dépôt de code officiel de l’app : <https://github.com/Stirling-Tools/Stirling-PDF>
- YunoHost Store : <https://apps.yunohost.org/app/stirling>
- Signaler un bug : <https://github.com/YunoHost-Apps/stirling_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/stirling_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
ou
sudo yunohost app upgrade stirling -u https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
