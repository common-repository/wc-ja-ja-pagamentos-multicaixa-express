=== Já-Já Pagamentos for WooCommerce - Payment with MULTICAIXA Express ===
Contributors: yellen
Tags: woocommerce, payment, pagamentos, gateway, multicaixa, angola, multibanco, atm, debit card, credit card, bank, ecommerce, e-commerce, emis, gpo, GPO, cartão de crédito, cartões, online, yellen, mcxe já-já pagamentos
Requires at least: 4.9
Tested up to: 6.3
Stable tag: 1.2.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

This plugin allows customers with an Angolan bank account to pay WooCommerce orders in Kwanza using MULTICAIXA Express through Já-Já pagamentos’s payment gateway. 
This plugin interacts with GPO (https://pagamentonline.emis.co.ao/online-payment-gateway/portal/), so to use it you will need a contract with EMIS and Já-Já Pagamentos.

== Description ==

This plugin will allow you to accept payment with MULTICAIXA Espress.

This plugin works with the [Já-Já Pagamentos] gateway, and a contract with an Angolan bank is required.

= Features: =

* Accepts payments with MULTICAIXA Express the top payment application in Angola;
* Automatically changes the order status to “Processing” (or “Completed” if the order only contains virtual downloadable products) and notifies both the customer and the store owner.
* GPO test environment support
* PHP7 tested and compatible

== Installation ==

* Use the included automatic install feature on your WordPress admin panel and search for "Já Já Pagamentos MULTICAIXA”.
* Go to WooCoomerce > Settings > Payments > MULTICAIXA Express and fill in the details provided by Já-Já Pagamentos and your bank in order to use this payment method. A contract with Já-Já Pagamentos and a bank is mandatory.
* Start receiving payments :-)

== Frequently Asked Questions ==

= How can I use the plugin with the Já Já Pagamentos test environment? =

You should return true to the `testmode` filter to activate the test mode with a simple checkbox.


== Changelog ==

= 1.0 =
* Initial release.
= 1.1 =
* Create redirect pages for payment with and without sucess.
= 1.2 =
* Support for purchase with QRCODE
= 1.3 =
* Support for HPOS
