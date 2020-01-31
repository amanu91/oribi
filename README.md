#  How To Install Magento 2 Oribi Module into the Store
Oribi Analytics
1. Log into your hosting space via a FTP client
2. Unzip extension package and upload them into Magento root directory(correct path is app/code/Oribi/Analytics)
3. Run the commands in the Magento 2 directory via CLI:
# Commands
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy (if this command not excuted add -f at the end)
# Permissions
set permissions for var/ generated/ pub/static/ directoy 777 recurcively.
