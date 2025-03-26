<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# Stirling PDF per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/stirling-pdf)](https://ci-apps.yunohost.org/ci/apps/stirling-pdf/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/stirling-pdf)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/stirling-pdf)

[![Instal·la Stirling PDF amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling-pdf)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar Stirling PDF de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

This is a robust, locally hosted web-based PDF manipulation tool. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

### Features

- Dark mode support.
- Custom download options
- Parallel file processing and downloads
- Custom 'Pipelines' to run multiple features in a queue
- API for integration with external scripts
- Optional Login and Authentication support (see here for documentation)
- Database Backup and Import (see here for documentation)


**Versió inclosa:** 0.45.0~ynh1

**Demo:** <https://stirlingpdf.io/>

## Captures de pantalla

![Captures de pantalla de Stirling PDF](./doc/screenshots/screenshot.jpg)

## Documentació i recursos

- Lloc web oficial de l'aplicació: <https://www.stirlingpdf.com/>
- Documentació oficial per l'usuari: <https://docs.stirlingpdf.com/>
- Documentació oficial per l'administrador: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Repositori oficial del codi de l'aplicació: <https://github.com/Stirling-Tools/Stirling-PDF>
- Botiga YunoHost: <https://apps.yunohost.org/app/stirling-pdf>
- Reportar un error: <https://github.com/YunoHost-Apps/stirling-pdf_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
o
sudo yunohost app upgrade stirling-pdf -u https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>
