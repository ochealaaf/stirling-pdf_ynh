<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Stirling PDF

[![集成程度](https://dash.yunohost.org/integration/stirling.svg)](https://ci-apps.yunohost.org/ci/apps/stirling/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/stirling.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/stirling.maintain.svg)

[![使用 YunoHost 安装 Stirling PDF](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Stirling PDF。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

This is a robust, locally hosted web-based PDF manipulation tool using Docker. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

Stirling PDF does not initiate any outbound calls for record-keeping or tracking purposes.

All files and PDFs exist either exclusively on the client side, reside in server memory only during task execution, or temporarily reside in a file solely for the execution of the task. Any file downloaded by the user will have been deleted from the server by that point.

**分发版本：** 0.29.0~ynh1

**演示：** <https://stirlingpdf.io/>

## 截图

![Stirling PDF 的截图](./doc/screenshots/screenshot.jpg)

## 文档与资源

- 官方应用网站： <https://www.stirlingpdf.com/>
- 官方用户文档： <https://docs.stirlingpdf.com/>
- 官方管理文档： <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- 上游应用代码库： <https://github.com/Stirling-Tools/Stirling-PDF>
- YunoHost 商店： <https://apps.yunohost.org/app/stirling>
- 报告 bug： <https://github.com/YunoHost-Apps/stirling_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/stirling_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
或
sudo yunohost app upgrade stirling -u https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
