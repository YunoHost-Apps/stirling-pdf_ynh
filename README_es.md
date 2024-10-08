<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Stirling PDF para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/stirling.svg)](https://ci-apps.yunohost.org/ci/apps/stirling/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/stirling.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/stirling.maintain.svg)

[![Instalar Stirling PDF con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarStirling PDF rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

This is a robust, locally hosted web-based PDF manipulation tool using Docker. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

Stirling PDF does not initiate any outbound calls for record-keeping or tracking purposes.

All files and PDFs exist either exclusively on the client side, reside in server memory only during task execution, or temporarily reside in a file solely for the execution of the task. Any file downloaded by the user will have been deleted from the server by that point.

**Versión actual:** 0.29.0~ynh1

**Demo:** <https://stirlingpdf.io/>

## Capturas

![Captura de Stirling PDF](./doc/screenshots/screenshot.jpg)

## Documentaciones y recursos

- Sitio web oficial: <https://www.stirlingpdf.com/>
- Documentación usuario oficial: <https://docs.stirlingpdf.com/>
- Documentación administrador oficial: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/Stirling-Tools/Stirling-PDF>
- Catálogo YunoHost: <https://apps.yunohost.org/app/stirling>
- Reportar un error: <https://github.com/YunoHost-Apps/stirling_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/stirling_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
o
sudo yunohost app upgrade stirling -u https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
