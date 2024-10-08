<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Stirling PDF YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/stirling.svg)](https://ci-apps.yunohost.org/ci/apps/stirling/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/stirling.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/stirling.maintain.svg)

[![Instalatu Stirling PDF YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Stirling PDF YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

This is a robust, locally hosted web-based PDF manipulation tool using Docker. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

Stirling PDF does not initiate any outbound calls for record-keeping or tracking purposes.

All files and PDFs exist either exclusively on the client side, reside in server memory only during task execution, or temporarily reside in a file solely for the execution of the task. Any file downloaded by the user will have been deleted from the server by that point.

**Paketatutako bertsioa:** 0.29.0~ynh1

**Demoa:** <https://stirlingpdf.io/>

## Pantaila-argazkiak

![Stirling PDF(r)en pantaila-argazkia](./doc/screenshots/screenshot.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.stirlingpdf.com/>
- Erabiltzaileen dokumentazio ofiziala: <https://docs.stirlingpdf.com/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Stirling-Tools/Stirling-PDF>
- YunoHost Denda: <https://apps.yunohost.org/app/stirling>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/stirling_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/stirling_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
edo
sudo yunohost app upgrade stirling -u https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
