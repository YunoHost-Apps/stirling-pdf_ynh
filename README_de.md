<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# Stirling PDF für YunoHost

[![Integrations-Level](https://apps.yunohost.org/badge/integration/stirling-pdf)](https://ci-apps.yunohost.org/ci/apps/stirling-pdf/)
![Funktionsstatus](https://apps.yunohost.org/badge/state/stirling-pdf)
![Wartungsstatus](https://apps.yunohost.org/badge/maintained/stirling-pdf)

[![Stirling PDF mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling-pdf)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie Stirling PDF schnell und einfach auf einem YunoHost-Server installieren.*  
> *Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

This is a robust, locally hosted web-based PDF manipulation tool. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

### Features

- Dark mode support.
- Custom download options
- Parallel file processing and downloads
- Custom 'Pipelines' to run multiple features in a queue
- API for integration with external scripts
- Optional Login and Authentication support (see here for documentation)
- Database Backup and Import (see here for documentation)


**Ausgelieferte Version:** 0.45.0~ynh1

**Demo:** <https://stirlingpdf.io/>

## Bildschirmfotos

![Bildschirmfotos von Stirling PDF](./doc/screenshots/screenshot.jpg)

## Dokumentation und Ressourcen

- Offizielle Website der App: <https://www.stirlingpdf.com/>
- Offizielle Benutzerdokumentation: <https://docs.stirlingpdf.com/>
- Offizielle Verwaltungsdokumentation: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Upstream App Repository: <https://github.com/Stirling-Tools/Stirling-PDF>
- YunoHost-Shop: <https://apps.yunohost.org/app/stirling-pdf>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/stirling-pdf_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [`testing` branch](https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing).

Um den `testing` Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
oder
sudo yunohost app upgrade stirling-pdf -u https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>
