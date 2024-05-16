<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Cjdns YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/cjdns.svg)](https://dash.yunohost.org/appci/app/cjdns) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/cjdns.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/cjdns.maintain.svg)

[![Instalatu Cjdns YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cjdns)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Cjdns YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Cjdns implements an encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. This provides near-zero-configuration networking, and prevents many of the security and scalability issues that plague existing networks.


**Paketatutako bertsioa:** 22.7~ynh2

## Pantaila-argazkiak

![Cjdns(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/cjdelisle/cjdns/>
- YunoHost Denda: <https://apps.yunohost.org/app/cjdns>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/cjdns_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
edo
sudo yunohost app upgrade cjdns -u https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
