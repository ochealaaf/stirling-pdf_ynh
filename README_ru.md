<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Stirling PDF для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/stirling.svg)](https://ci-apps.yunohost.org/ci/apps/stirling/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/stirling.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/stirling.maintain.svg)

[![Установите Stirling PDF с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Stirling PDF быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

This is a robust, locally hosted web-based PDF manipulation tool using Docker. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

Stirling PDF does not initiate any outbound calls for record-keeping or tracking purposes.

All files and PDFs exist either exclusively on the client side, reside in server memory only during task execution, or temporarily reside in a file solely for the execution of the task. Any file downloaded by the user will have been deleted from the server by that point.

**Поставляемая версия:** 0.29.0~ynh1

**Демо-версия:** <https://stirlingpdf.io/>

## Снимки экрана

![Снимок экрана Stirling PDF](./doc/screenshots/screenshot.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.stirlingpdf.com/>
- Официальная документация пользователя: <https://docs.stirlingpdf.com/>
- Официальная документация администратора: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Репозиторий кода главной ветки приложения: <https://github.com/Stirling-Tools/Stirling-PDF>
- Магазин YunoHost: <https://apps.yunohost.org/app/stirling>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/stirling_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/stirling_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
или
sudo yunohost app upgrade stirling -u https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
