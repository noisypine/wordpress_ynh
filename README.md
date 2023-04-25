<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# WordPress for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wordpress.svg)](https://dash.yunohost.org/appci/app/wordpress) ![Working status](https://ci-apps.yunohost.org/ci/badges/wordpress.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/wordpress.maintain.svg)

[![Install WordPress with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wordpress)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install WordPress quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

WordPress is open source software you can use to create a beautiful website, blog, or app.  
With this package, you can even activate the [multisite](https://wordpress.org/support/article/glossary/#multisite) option.


**Shipped version:** 6.2~ynh1

## Screenshots

![Screenshot of WordPress](./doc/screenshots/screen-themes.png)

## :red_circle: Antifeatures

- **Non-free Addons**: Promotes other non-free applications or plugins.

- **Paid content**: Promotes or depends, entirely or partially, on a paid service.

## Documentation and resources

* Official app website: <https://wordpress.org/>
* Official admin documentation: <https://codex.wordpress.org/>
* Upstream app code repository: <https://core.trac.wordpress.org/browser>
* YunoHost documentation for this app: <https://yunohost.org/app_wordpress>
* Report a bug: <https://github.com/YunoHost-Apps/wordpress_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/wordpress_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/wordpress_ynh/tree/testing --debug
or
sudo yunohost app upgrade wordpress -u https://github.com/YunoHost-Apps/wordpress_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
