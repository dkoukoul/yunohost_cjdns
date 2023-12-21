<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Cjdns for YunoHost

[![Integration level](https://dash.yunohost.org/integration/cjdns.svg)](https://dash.yunohost.org/appci/app/cjdns) ![Working status](https://ci-apps.yunohost.org/ci/badges/cjdns.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/cjdns.maintain.svg)

[![Install Cjdns with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cjdns)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Cjdns quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Cjdns implements an encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. This provides near-zero-configuration networking, and prevents many of the security and scalability issues that plague existing networks.


**Shipped version:** 22.7~ynh1

## Screenshots

![Screenshot of Cjdns](./doc/screenshots/screenshot.png)

## Documentation and resources

* Upstream app code repository: <https://github.com/cjdelisle/cjdns/>
* YunoHost Store: <https://apps.yunohost.org/app/cjdns>
* Report a bug: <https://github.com/YunoHost-Apps/cjdns_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
or
sudo yunohost app upgrade cjdns -u https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
