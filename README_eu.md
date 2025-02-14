<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Stirling PDF YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/stirling-pdf)](https://ci-apps.yunohost.org/ci/apps/stirling-pdf/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/stirling-pdf)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/stirling-pdf)

[![Instalatu Stirling PDF YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling-pdf)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Stirling PDF YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

This is a robust, locally hosted web-based PDF manipulation tool. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

### Features

- Dark mode support.
- Custom download options
- Parallel file processing and downloads
- Custom 'Pipelines' to run multiple features in a queue
- API for integration with external scripts
- Optional Login and Authentication support (see here for documentation)
- Database Backup and Import (see here for documentation)


**Paketatutako bertsioa:** 0.41.0~ynh2

**Demoa:** <https://stirlingpdf.io/>

## Pantaila-argazkiak

![Stirling PDF(r)en pantaila-argazkia](./doc/screenshots/screenshot.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.stirlingpdf.com/>
- Erabiltzaileen dokumentazio ofiziala: <https://docs.stirlingpdf.com/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Stirling-Tools/Stirling-PDF>
- YunoHost Denda: <https://apps.yunohost.org/app/stirling-pdf>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/stirling-pdf_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
edo
sudo yunohost app upgrade stirling-pdf -u https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
