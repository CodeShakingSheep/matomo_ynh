# Matomo for YunoHost

[![Integration level](https://dash.yunohost.org/integration/matomo.svg)](https://dash.yunohost.org/appci/app/matomo) ![](https://ci-apps.yunohost.org/ci/badges/matomo.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/matomo.maintain.svg)  
[![Install Matomo with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=matomo)

> *This package allows you to install Matomo quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Matomo is the only analytics platform that gives you full control over your data and more:

- Free open-source software
- 100% data ownership
- User privacy protection
- User-centric insights
- Customisable and extensible
- Easy to use
- No data limits

**Shipped version:** 4.0.1

## Screenshots

![](https://img.matomo.org/spai/w_660+q_lossless+ret_img+to_webp/https://static.matomo.org/wp-content/uploads/2019/03/matomo-analytics-dashboard.png)

## Demo

* [Official demo](https://demo.matomo.org)

## Configuration

1. The app will require to complete the registration process after the instllation is complete by **visiting the domain** on  which Matomo is installed.
1. The MySQL database credentials will be sent to the **admin mail**. Fill these details while doing the registration process.
1. No LDAP support yet for the app.

## Documentation

 * Official documentation: https://matomo.org/docs
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/matomo%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/matomo/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/matomo%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/matomo/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/matomo_ynh/issues
 * App website: https://matomo.org/
 * Upstream app repository: https://github.com/matomo-org/matomo
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/matomo_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
or
sudo yunohost app upgrade matomo -u https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
```
