<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Stirling PDF dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/stirling-pdf)](https://ci-apps.yunohost.org/ci/apps/stirling-pdf/)
![Status działania](https://apps.yunohost.org/badge/state/stirling-pdf)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/stirling-pdf)

[![Zainstaluj Stirling PDF z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling-pdf)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Stirling PDF na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

This is a robust, locally hosted web-based PDF manipulation tool. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

### Features

- Dark mode support.
- Custom download options
- Parallel file processing and downloads
- Custom 'Pipelines' to run multiple features in a queue
- API for integration with external scripts
- Optional Login and Authentication support (see here for documentation)
- Database Backup and Import (see here for documentation)


**Dostarczona wersja:** 0.44.3~ynh1

**Demo:** <https://stirlingpdf.io/>

## Zrzuty ekranu

![Zrzut ekranu z Stirling PDF](./doc/screenshots/screenshot.jpg)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://www.stirlingpdf.com/>
- Oficjalna dokumentacja: <https://docs.stirlingpdf.com/>
- Oficjalna dokumentacja dla administratora: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Repozytorium z kodem źródłowym: <https://github.com/Stirling-Tools/Stirling-PDF>
- Sklep YunoHost: <https://apps.yunohost.org/app/stirling-pdf>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/stirling-pdf_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
lub
sudo yunohost app upgrade stirling-pdf -u https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
