<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Cjdns pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/cjdns.svg)](https://ci-apps.yunohost.org/ci/apps/cjdns/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/cjdns.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/cjdns.maintain.svg)

[![Installer Cjdns avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cjdns)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Cjdns rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Cjdns implémente un réseau IPv6 crypté utilisant une cryptographie à clé publique pour l'attribution des adresses et une table de hachage distribuée pour le routage. Cela fournit une configuration réseau proche de zéro et évite de nombreux problèmes de sécurité et d'évolutivité qui affectent les réseaux existants.

**Version incluse :** 22.7~ynh2

## Captures d’écran

![Capture d’écran de Cjdns](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/cjdelisle/cjdns/>
- YunoHost Store : <https://apps.yunohost.org/app/cjdns>
- Signaler un bug : <https://github.com/YunoHost-Apps/cjdns_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
ou
sudo yunohost app upgrade cjdns -u https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
