<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Stirling PDF para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/stirling-pdf)](https://ci-apps.yunohost.org/ci/apps/stirling-pdf/)
![Estado funcional](https://apps.yunohost.org/badge/state/stirling-pdf)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/stirling-pdf)

[![Instalar Stirling PDF con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling-pdf)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarStirling PDF rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

This is a robust, locally hosted web-based PDF manipulation tool. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

### Features

- Dark mode support.
- Custom download options
- Parallel file processing and downloads
- Custom 'Pipelines' to run multiple features in a queue
- API for integration with external scripts
- Optional Login and Authentication support (see here for documentation)
- Database Backup and Import (see here for documentation)


**Versión actual:** 0.41.0~ynh1

**Demo:** <https://stirlingpdf.io/>

## Capturas

![Captura de Stirling PDF](./doc/screenshots/screenshot.jpg)

## Documentaciones y recursos

- Sitio web oficial: <https://www.stirlingpdf.com/>
- Documentación usuario oficial: <https://docs.stirlingpdf.com/>
- Documentación administrador oficial: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/Stirling-Tools/Stirling-PDF>
- Catálogo YunoHost: <https://apps.yunohost.org/app/stirling-pdf>
- Reportar un error: <https://github.com/YunoHost-Apps/stirling-pdf_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
o
sudo yunohost app upgrade stirling-pdf -u https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
