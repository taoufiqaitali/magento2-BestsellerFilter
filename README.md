# Magento 2  best seller filter

Magento 2 custom module to add custom best seller filter to product list toolbar

* Developer: Taoufiq Ait Ali
* Website: http://asktaw.com
* Contact: <mailto:contact@asktaw.com>


### Manual Installation

 * Unzip the file
 * Create a folder {Magento root}/app/code/Taoufiqaitali/BestsellerFilter
 * Copy the content from the unzip folder

## Enable extension

```
php bin/magento module:enable Taoufiqaitali_BestsellerFilter
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento cache:flush
php bin/magento setup:static-content:deploy
```
