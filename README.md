<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# code-server for YunoHost

[![Integration level](https://dash.yunohost.org/integration/code-server.svg)](https://dash.yunohost.org/appci/app/code-server) ![](https://ci-apps.yunohost.org/ci/badges/code-server.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/code-server.maintain.svg)  
[![Install code-server with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=code-server)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install code-server quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Run VS Code on your server and access it in the browser

**Shipped version:** 4.0.1~ynh1



## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

### Installation

* The package does not create a dedicated system user, rather during installation you are asked what user you want code-server to run as. **Don't give access to users you don't fully trust!**

### Limitations

* Requires a dedicated domain
* Single-user, no LDAP
* Subdomains for services on ports (like 8080.code-server-domain.tld) are not supported

## Documentation and resources

* Official app website: https://github.com/cdr/code-server
* Official user documentation: https://github.com/cdr/code-server/tree/main/docs
* Official admin documentation: https://github.com/cdr/code-server/tree/main/docs
* Upstream app code repository: https://github.com/cdr/code-server
* YunoHost documentation for this app: https://yunohost.org/app_code-server
* Report a bug: https://github.com/YunoHost-Apps/code-server_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/code-server_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/code-server_ynh/tree/testing --debug
or
sudo yunohost app upgrade code-server -u https://github.com/YunoHost-Apps/code-server_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps