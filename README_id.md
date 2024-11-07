<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Cjdns untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/cjdns.svg)](https://ci-apps.yunohost.org/ci/apps/cjdns/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/cjdns.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/cjdns.maintain.svg)

[![Pasang Cjdns dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cjdns)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Cjdns secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Cjdns implements an encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. This provides near-zero-configuration networking, and prevents many of the security and scalability issues that plague existing networks.


**Versi terkirim:** 22.7~ynh2

## Tangkapan Layar

![Tangkapan Layar pada Cjdns](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://github.com/cjdelisle/cjdns/>
- Gudang YunoHost: <https://apps.yunohost.org/app/cjdns>
- Laporkan bug: <https://github.com/YunoHost-Apps/cjdns_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
atau
sudo yunohost app upgrade cjdns -u https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
