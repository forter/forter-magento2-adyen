# Magento 2 Forter Fraud Detection Module (Adyen)

---

The extension is build in order to provide example for merchents on how to override there extension.

## Install manually under app/code
Download & place the contents of this repository under {YOUR-MAGENTO2-ROOT-DIR}/app/code/Forter/Adyen  
Then, run the following commands under your Magento 2 root dir:

```
php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

##  Notes
* This extension requires an installation of the forter_forter module, it can't be installed without the forter_forter module installed and enabled.
* As best practice when overriding the module, prefer using Before / After rather then Around, also, you should use plugin before override.

---

https://www.forter.com/

© 2020 Forter.
All rights reserved.

![Forter Logo](https://upload.wikimedia.org/wikipedia/commons/5/51/Forter_Logo_Blue_Web-3.png)
