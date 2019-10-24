
# Web Tail Pty Ltd - ZipPay Plugin
 NopCommerce plugin to enable ZipPay as a payment method
 
 Supported Versions: 4.10, 4.20, 4.30
 
This is a plugin which implements ZipPay as a payment method for NopCommerce. The project is designed for commercial use and has the following features/functionality:
 
 - Full feature checkout for the ZipPay merchant API in NopCommerce.
 - Features a sandbox/production mode.
 - Features 
 - Features multiple capture modes.
	 1. Authorize - Used to pre-authorize a purchase and place a hold on the customers credit card for the order amount.
	 2. Capture - Used to immediately authorize the full transaction amount and begin the funds transfer process.
 - Features additional fees functionality to be charged for the use of this payment method.
	1. Additional fees can also be a percentage of the total order.
.
 

## Installation

1. Download the plugin from the NopCommerce [marketplace](https://www.nopcommerce.com/marketplace.aspx).
2.  Connect to your NopCommerce site and extract the archive to /site/wwwroot/Plugins/.
3.  Navigate to https://yoursite.com/Admin/Plugin/List.
4. Find **'Credit Card (Stripe)'** and press install.
5. Restart site to apply changes.
6. Configure your API keys and press save.
