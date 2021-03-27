# TiddlyWiki pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/tiddlywiki.svg)](https://dash.yunohost.org/appci/app/tiddlywiki) ![](https://ci-apps.yunohost.org/ci/badges/tiddlywiki.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/tiddlywiki.maintain.svg)  
[![Installer TiddlyWiki avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tiddlywiki)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d’installer TiddlyWiki rapidement et simplement sur un serveur YunoHost.  
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble
TiddlyWiki est un cahier Web personnel non linéaire que tout le monde peut utiliser et conserver pour toujours, indépendamment de toute entreprise.
TiddlyWiki est un wiki interactif complet en JavaScript. Il peut être utilisé comme un seul fichier HTML dans le navigateur ou comme une puissante application Node.js.

**Shipped version:** 5.1.23

## Captures d’écran

![](screenshot.png)

## Démo

* [Démo officielle](https://tiddlywiki.com/)

## Documentation

 * Documentation officielle : https://tiddlywiki.com/languages/fr-FR/index.html
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/tiddlywiki%40%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/tiddlywiki/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/tiddlywiki%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/tiddlywiki/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/tiddlywiki_ynh/issues
 * Site de l'application : https://tiddlywiki.com/
 * Dépôt de l’application principale : https://github.com/Jermolene/TiddlyWiki5
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/tiddlywiki_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/tiddlywiki_ynh/tree/testing --debug
ou
sudo yunohost app upgrade tiddlywiki -u https://github.com/YunoHost-Apps/tiddlywiki_ynh/tree/testing --debug
```
