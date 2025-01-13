<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Stirling PDF для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/stirling-pdf)](https://ci-apps.yunohost.org/ci/apps/stirling-pdf/)
![Состояние работы](https://apps.yunohost.org/badge/state/stirling-pdf)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/stirling-pdf)

[![Установите Stirling PDF с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling-pdf)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Stirling PDF быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

This is a robust, locally hosted web-based PDF manipulation tool. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

### Features

- Dark mode support.
- Custom download options
- Parallel file processing and downloads
- Custom 'Pipelines' to run multiple features in a queue
- API for integration with external scripts
- Optional Login and Authentication support (see here for documentation)
- Database Backup and Import (see here for documentation)


**Поставляемая версия:** 0.29.0~ynh2

**Демо-версия:** <https://stirlingpdf.io/>

## Снимки экрана

![Снимок экрана Stirling PDF](./doc/screenshots/screenshot.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.stirlingpdf.com/>
- Официальная документация пользователя: <https://docs.stirlingpdf.com/>
- Официальная документация администратора: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Репозиторий кода главной ветки приложения: <https://github.com/Stirling-Tools/Stirling-PDF>
- Магазин YunoHost: <https://apps.yunohost.org/app/stirling-pdf>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/stirling-pdf_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
или
sudo yunohost app upgrade stirling-pdf -u https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
