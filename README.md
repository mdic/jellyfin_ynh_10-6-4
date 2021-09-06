# Jellyfin app for YunoHost
Jellyfin Server

**Shipped version:** 10.6.1

- [Yunohost project](https://yunohost.org)
- [Jellyfin website](https://github.com/jellyfin/jellyfin)

![](https://www.ostechnix.com/wp-content/uploads/2019/03/jellyfin-logo-720x340.png)


[![Install Jellyfin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=jellyfin)


### Installing guide

 App can be installed by YunoHost **admin web-interface** or by **running following command**:

        $ sudo yunohost app install https://github.com/YunoHost-Apps/jellyfin_ynh

### Upgrade this package:

        $ sudo yunohost app upgrade jellyfin -u https://github.com/YunoHost-Apps/jellyfin_ynh

### Note
 - This has only been tested on amd64 architecture
 - With the new 10.6 version, Jellyfin is now split across 3 different packages: server, web, and a meta package; previous versions had only one single package. The script now collects all needed packages (plus the ffmpeg one) and installs them using the same procedure used to install versions < 10.6.
 - ffmpeg has been kept at version 4.2.1.7 because the newer version (4.3.1.1) is not supported by Debian Stretch.
