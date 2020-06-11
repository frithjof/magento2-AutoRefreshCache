# magento2-AutoRefreshCache
Magento 2 module to automatically refresh cache using cron.

Please run these commands in CLI 
php bin/magentosetup:upgrade
php bin/magento cache:flush

make sure cron:run is in your crontab

this is based on https://www.emiprotechnologies.com/technical_notes/magento-technical-notes-60/post/automatically-refresh-cache-using-cron-in-magento-2-484

this is just so you can easily use it as a composer module
