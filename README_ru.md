<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Cjdns для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/cjdns.svg)](https://ci-apps.yunohost.org/ci/apps/cjdns/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/cjdns.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/cjdns.maintain.svg)

[![Установите Cjdns с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cjdns)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Cjdns быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Cjdns implements an encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. This provides near-zero-configuration networking, and prevents many of the security and scalability issues that plague existing networks.


**Поставляемая версия:** 22.7~ynh2

## Снимки экрана

![Снимок экрана Cjdns](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Репозиторий кода главной ветки приложения: <https://github.com/cjdelisle/cjdns/>
- Магазин YunoHost: <https://apps.yunohost.org/app/cjdns>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/cjdns_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
или
sudo yunohost app upgrade cjdns -u https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
