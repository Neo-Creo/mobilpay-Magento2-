# mobilpay-Magento2-
Payment gateway for Mobilpay on Magento 2 CE

Installation Guide :

Paste the module in app/code directory of your magento installation and execute following commands ;

sudo php bin/magento setup:upgrade
sudo php bin/magento setup:static-content:deploy
sudo chmod 777 -R var pub


Please do remember to enable payment method from stores->configuration->sales->payment methods->mobilpay
Also disable test mode and provide your signature id and other info in required fields.
