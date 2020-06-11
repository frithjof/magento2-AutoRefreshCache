# magento2-AutoRefreshCache
Magento 2 module to automatically refresh cache using cron.
For many shops you want to get changes to frontend as soon as possible and you are annoyed by clicking through cache refresh.

Install

**composer require gfe/autorefreshcache:dev-master**

Please run these commands in CLI 

php bin/magento setup:upgrade

php bin/magento cache:flush

php bin/magento setup:di:compile

make sure cron:run is in your crontab

this is based on https://www.emiprotechnologies.com/technical_notes/magento-technical-notes-60/post/automatically-refresh-cache-using-cron-in-magento-2-484

this is just so you can easily use it as a composer module
