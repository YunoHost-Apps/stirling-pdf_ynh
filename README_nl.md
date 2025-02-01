<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Stirling PDF voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/stirling-pdf)](https://ci-apps.yunohost.org/ci/apps/stirling-pdf/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/stirling-pdf)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/stirling-pdf)

[![Stirling PDF met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling-pdf)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Stirling PDF snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

This is a robust, locally hosted web-based PDF manipulation tool. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

### Features

- Dark mode support.
- Custom download options
- Parallel file processing and downloads
- Custom 'Pipelines' to run multiple features in a queue
- API for integration with external scripts
- Optional Login and Authentication support (see here for documentation)
- Database Backup and Import (see here for documentation)


**Geleverde versie:** 0.40.0~ynh1

**Demo:** <https://stirlingpdf.io/>

## Schermafdrukken

![Schermafdrukken van Stirling PDF](./doc/screenshots/screenshot.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://www.stirlingpdf.com/>
- Officiele gebruikersdocumentatie: <https://docs.stirlingpdf.com/>
- Officiele beheerdersdocumentatie: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Upstream app codedepot: <https://github.com/Stirling-Tools/Stirling-PDF>
- YunoHost-store: <https://apps.yunohost.org/app/stirling-pdf>
- Meld een bug: <https://github.com/YunoHost-Apps/stirling-pdf_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
of
sudo yunohost app upgrade stirling-pdf -u https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
