<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Stirling PDF para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/stirling.svg)](https://ci-apps.yunohost.org/ci/apps/stirling/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/stirling.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/stirling.maintain.svg)

[![Instalar Stirling PDF con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Stirling PDF de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

This is a robust, locally hosted web-based PDF manipulation tool using Docker. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

Stirling PDF does not initiate any outbound calls for record-keeping or tracking purposes.

All files and PDFs exist either exclusively on the client side, reside in server memory only during task execution, or temporarily reside in a file solely for the execution of the task. Any file downloaded by the user will have been deleted from the server by that point.

**Versión proporcionada:** 0.29.0~ynh1

**Demo:** <https://stirlingpdf.io/>

## Capturas de pantalla

![Captura de pantalla de Stirling PDF](./doc/screenshots/screenshot.jpg)

## Documentación e recursos

- Web oficial da app: <https://www.stirlingpdf.com/>
- Documentación oficial para usuarias: <https://docs.stirlingpdf.com/>
- Documentación oficial para admin: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Repositorio de orixe do código: <https://github.com/Stirling-Tools/Stirling-PDF>
- Tenda YunoHost: <https://apps.yunohost.org/app/stirling>
- Informar dun problema: <https://github.com/YunoHost-Apps/stirling_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/stirling_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
ou
sudo yunohost app upgrade stirling -u https://github.com/YunoHost-Apps/stirling_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
