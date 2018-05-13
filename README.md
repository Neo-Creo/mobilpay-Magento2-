# mobilpay-Magento2-
Payment gateway for Mobilpay on Magento 2 CE

<b>Installation Guide :</b> <br><br>

Paste the module in app/code directory of your magento installation and execute following commands ;<br><br>
<pre>
sudo php bin/magento setup:upgrade
sudo php bin/magento setup:static-content:deploy
sudo chmod 777 -R var pub
</pre>
<br>
Please do remember to enable payment method from <b>stores->configuration->sales->payment methods->mobilpay</b><br>
Also disable test mode, provide your signature id and other info in required fields.<br>
