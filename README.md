mod-aceshop
===========
PayFast Ace Shop Payment v1.0.0 for Ace Shop v4.*
-------------------------------------------------------
Copyright (c) 2008 PayFast (Pty) Ltd
You (being anyone who is not PayFast (Pty) Ltd) may download and use this plugin / code in your own website in conjunction with a registered and active PayFast account. If your PayFast account is terminated for any reason, you may not use this plugin / code or part thereof.
Except as expressly indicated in this licence, you may not use, copy, modify or distribute this plugin / code or part thereof in any way.

INTEGRATION:
1. Unzip the module to a temporary location on your computer
2. Copy the folders in the archive to your base ‘Joomla’ folder
- This should NOT overwrite any existing files or folders and merely supplement them with the PayFast files
- This is however, dependent on the FTP program you use
3. Login to the Control Panel of your Joomla installation
4. Navigate to the Components > Aceshop > Dashboard, then Extensions > Payments
5. Scroll down to the PayFast.co.za payment method and click the ‘Install’ button to install the module
6. The PayFast options will then be shown, select the payment status for ‘completed’, ‘failed’ and ‘pending’ payments, select the sandbox mode, enable the payment module and click ‘Save’.
7. The module is now ready to be tested with the Sandbox. To test with the sandbox, use the following login credentials when redirected to the PayFast site:
- Username: sbtu01@payfast.co.za
- Password: clientpass

How can I test that it is working correctly?
If you followed the installation instructions above, the module is in “test” mode and you can test it by purchasing from your site as a buyer normally would. You will be redirected to PayFast for payment and can login with the user account detailed above and make payment using the balance in their wallet.

You will not be able to directly “test” a credit card, Instant EFT or Ukash payment in the sandbox, but you don’t really need to. The inputs to and outputs from PayFast are exactly the same, no matter which payment method is used, so using the wallet of the test user will give you exactly the same results as if you had used another payment method.

I’m ready to go live! What do I do?
In order to make the module “LIVE”, follow the instructions below:

1. Login to the Control Panel section of your Joomla system
2. Navigate to the Components > Aceshop > Dashboard, and then Extensions > Payments page
3. Under PayFast.co.za, click on the “Edit” link
4. In the PayFast Settings block, use the following settings:
5. Set Sandbox Mode = “No”
6. Merchant ID = Integration Page>
7. Merchant Key = Integration Page>
8. Click Save

************************************************************************

 Please see the URL below for all information concerning this module:

       https://www.payfast.co.za/shopping-carts/joomla-aceshop/

************************************************************************

