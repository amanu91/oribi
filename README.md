#  How To Install Magento 2 Oribi Module into the Store
Oribi Analytics
1. Log into your hosting space via a FTP client
2. Unzip extension package and upload them into Magento root directory(correct path is app/code/Oribi/Analytics)
3. Run the commands in the Magento 2 directory via CLI at roort directory of magento2

# Commands
1. php bin/magento setup:upgrade
2. php bin/magento setup:di:compile
3. php bin/magento setup:static-content:deploy (if this command not excuted add -f at the end)
4. php bin/magento c:f

# Permissions
set permissions for var/ generated/ pub/static/ directoy 777 recurcively.
Command : chmod 777 var/* generated/* pub/static/* -R

# After Installation

You can see ORIBI menu in backend. 

# Configuration

1. Enable Or Disable the module
2. Add oribi token
3. Select track purchases.
4. If you dont know the token you will add script code provided by the oribi.

After that you can track your store events with oribi.
