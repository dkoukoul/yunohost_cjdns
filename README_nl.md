<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Cjdns voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/cjdns.svg)](https://ci-apps.yunohost.org/ci/apps/cjdns/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/cjdns.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/cjdns.maintain.svg)

[![Cjdns met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cjdns)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Cjdns snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Cjdns implements an encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. This provides near-zero-configuration networking, and prevents many of the security and scalability issues that plague existing networks.


**Geleverde versie:** 22.7~ynh2

## Schermafdrukken

![Schermafdrukken van Cjdns](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Upstream app codedepot: <https://github.com/cjdelisle/cjdns/>
- YunoHost-store: <https://apps.yunohost.org/app/cjdns>
- Meld een bug: <https://github.com/YunoHost-Apps/cjdns_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
of
sudo yunohost app upgrade cjdns -u https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
