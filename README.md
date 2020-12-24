# ipayos-woocommerce-plugin
Integrating iPayOS with your Wordpress WooCommerce website is super easy with this Plugin. You just have to download it from here, upload it to your server &amp; configure it with your iPayOS Account details to start accepting online payments via iPayOS.

How to install these plugins

1.Navigate to the ‘Add New’ in the plugins dashboard
2.Navigate to the ‘Upload’ area
3.Select woocommerce.zip from your computer
4.Click ‘Install Now’
5.Activate the plugin in the Plugin dashboard
6.Then Select ipayos.zip from your computer
7.Click ‘Install Now’
8.Activate the plugin in the Plugin dashboard

How to run
Please follow these 3 steps

Step-1
Next go to ipayos-web-client-demo folder and open ncc_init_redirect.php file
Replace this redirect url "http://localhost/your-wordpress-path-folder/index.php/checkout/order-received/" insted of "http://localhost/yazhii-ncc-client/ncc_complete.php"

Step-2
Next go to your-wordpress-path-folder\wp-content\plugins\ipayos\ open ipayos-payments-woocommerce.php file 
Look at line 38 past this redirect url "http://localhost/your-clint-demo-folder/"  insted of "http://localhost/yazhii-ncc-client/"

Step-3
Deploy in WEB Server (Eg. Apache)
Browse "http://localhost/your-wordpress-installon-folder"