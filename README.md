# Wordpress for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wordpress.svg)](https://ci-apps.yunohost.org/jenkins/job/wordpress%20%28Official%29/lastBuild/consoleFull)  
[![Install Wordpress with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=wordpress)

> *This package allow you to install wordpress quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
WordPress is open source software you can use to create a beautiful website, blog, or app.  
With this package, you can even activate the [multisite](https://codex.wordpress.org/Glossary#Multisite) option.

**Shipped version:** 4.8

## Screenshots

![](https://s.w.org/images/home/screen-themes.png?1)

## Configuration

Use the admin panel of your wordpress to configure this app.

## Documentation

 * Official documentation: https://codex.wordpress.org/
 * YunoHost documentation: There no other documentations, feel free to contribute.

## YunoHost specific features

 * Integration with YunoHost users and SSO:
   * private mode: Blog only accessible by YunoHost users
   * public mode: Visible by anyone, YunoHost users automatically connected
 * Automatic update of wordpress core, plugins and themes
 * Allow to set up a [multisite](https://codex.wordpress.org/Glossary#Multisite) instance.

#### Multi-users support

Supported, with LDAP and SSO.

#### Supported architectures

* Tested on x86_64
* Tested on RaspberryPi

## Limitations

* Multisite only available on subdirectories.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/wordpress_ynh/issues
 * Wordpress website: https://wordpress.org/
 * YunoHost website: https://yunohost.org/

---

Developers infos
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/wordpress_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wordpress_ynh/tree/testing --verbose
or
sudo yunohost app upgrade wordpress -u https://github.com/YunoHost-Apps/wordpress_ynh/tree/testing --verbose
```
