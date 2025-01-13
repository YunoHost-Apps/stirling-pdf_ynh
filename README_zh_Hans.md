<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Stirling PDF

[![集成程度](https://apps.yunohost.org/badge/integration/stirling-pdf)](https://ci-apps.yunohost.org/ci/apps/stirling-pdf/)
![工作状态](https://apps.yunohost.org/badge/state/stirling-pdf)
![维护状态](https://apps.yunohost.org/badge/maintained/stirling-pdf)

[![使用 YunoHost 安装 Stirling PDF](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling-pdf)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Stirling PDF。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

This is a robust, locally hosted web-based PDF manipulation tool. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

### Features

- Dark mode support.
- Custom download options
- Parallel file processing and downloads
- Custom 'Pipelines' to run multiple features in a queue
- API for integration with external scripts
- Optional Login and Authentication support (see here for documentation)
- Database Backup and Import (see here for documentation)


**分发版本：** 0.29.0~ynh2

**演示：** <https://stirlingpdf.io/>

## 截图

![Stirling PDF 的截图](./doc/screenshots/screenshot.jpg)

## 文档与资源

- 官方应用网站： <https://www.stirlingpdf.com/>
- 官方用户文档： <https://docs.stirlingpdf.com/>
- 官方管理文档： <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- 上游应用代码库： <https://github.com/Stirling-Tools/Stirling-PDF>
- YunoHost 商店： <https://apps.yunohost.org/app/stirling-pdf>
- 报告 bug： <https://github.com/YunoHost-Apps/stirling-pdf_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
或
sudo yunohost app upgrade stirling-pdf -u https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
