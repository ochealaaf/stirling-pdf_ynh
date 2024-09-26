<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Stirling PDF voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/stirling.svg)](https://ci-apps.yunohost.org/ci/apps/stirling/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/stirling.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/stirling.maintain.svg)

[![Stirling PDF met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Stirling PDF snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

This is a robust, locally hosted web-based PDF manipulation tool using Docker. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

Stirling PDF does not initiate any outbound calls for record-keeping or tracking purposes.

All files and PDFs exist either exclusively on the client side, reside in server memory only during task execution, or temporarily reside in a file solely for the execution of the task. Any file downloaded by the user will have been deleted from the server by that point.

**Geleverde versie:** 0.29.0~ynh1

**Demo:** <https://stirlingpdf.io/>

## Schermafdrukken

![Schermafdrukken van Stirling PDF](./doc/screenshots/screenshot.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://www.stirlingpdf.com/>
- Officiele gebruikersdocumentatie: <https://docs.stirlingpdf.com/>
- Officiele beheerdersdocumentatie: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Upstream app codedepot: <https://github.com/Stirling-Tools/Stirling-PDF>
- YunoHost-store: <https://apps.yunohost.org/app/stirling>
- Meld een bug: <https://github.com/YunoHost-Apps/stirling_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/stirling_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
of
sudo yunohost app upgrade stirling -u https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
