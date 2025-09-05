# aapanel-v7.X-lifetime

_AAPanel v7.x Lifetime_

# Update
**v7.0.24**

1. Fixed: Issue where \"domain not found\" prompt appears during SSL renewal
2. Fixed: Known issues in the Files module


`Unlock All Pro Features - All Extension Plugins`

# Installation & Upgrade Scripts for aapanel v7.0.24

## Quick Installation

To install **aapanel v7.0.24** on your server, run the following command:

```bash
URL=https://cloud.hungnh.com/install/install_7.0_en.sh && \
if [ -f /usr/bin/curl ]; then \
  curl -ksSO $URL ; \
else \
  wget -O install_7.0_en.sh $URL; \
fi; \
bash install_7.0_en.sh
```

This script will:
- Automatically detect whether `curl` or `wget` is available.
- Download and execute the installation script.

---

## Upgrade Panel

To upgrade your aapanel installation to the latest 7.x version, use:

```bash
curl https://cloud.hungnh.com/install/update_7.x_en.sh | bash
```

This command will download and run the upgrade script directly.

---

**For detailed instructions and troubleshooting, visit:**  
[https://cloud.hungnh.com](https://cloud.hungnh.com)

---
**Maintained by:** @vnsur/aapanel-v7-lifetime

**Uninstall**

`sudo bt stop &&sudo update-rc.d -f bt remove &&sudo rm -f /etc/init.d/bt &&sudo rm -rf /www/server/panel`

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=vnsur/aapanel-v7-lifetime&type=Date)](https://star-history.com/#vnsur/aapanel-v7-lifetime&Date)

# Changelog

**v7.0.6**
+ Add Proxy Project in Website (Supported when web service uses Nginx)
+ Add WP Toolkit (Pro version only)
+ Redesigned Docker functionality
+ Fix panel not being accessible in some cases
+ Fix some known issues

**v7.0.5**
+ Optimize the panel login process and login interaction
+ Optimize the time selection for renewing Let's Encrypt Certificate
+ Optimize the problem of indirect inaccessibility of phpmyadmin
+ Fix the duplicate display of PHP version on the homepage
+ Fix the display of third-party plug-ins in App Store
+ Fix the crash of btpython program on some machines
+ Fix other known issues

  
**v7.0.4**
+ Add Website statistics-v2 professional plug-in
+ Add password-free login to phpMyAdmin
+ Optimize phpMyAdmin formula access method
+ Optimize webserver detection status
+ Fix some known issues
