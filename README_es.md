<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Cjdns para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/cjdns.svg)](https://ci-apps.yunohost.org/ci/apps/cjdns/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/cjdns.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/cjdns.maintain.svg)

[![Instalar Cjdns con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cjdns)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarCjdns rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Cjdns implements an encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. This provides near-zero-configuration networking, and prevents many of the security and scalability issues that plague existing networks.


**Versión actual:** 22.7~ynh2

## Capturas

![Captura de Cjdns](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/cjdelisle/cjdns/>
- Catálogo YunoHost: <https://apps.yunohost.org/app/cjdns>
- Reportar un error: <https://github.com/YunoHost-Apps/cjdns_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
o
sudo yunohost app upgrade cjdns -u https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
