# Artemis Payment Gateway for WooCommerce orders via Stellar.

Accept payment for WooCommerce orders via Stellar  (both XLM and other tokens built on the Stellar Platform).

No registration and No Fees.

[Stellar](https://stellar.org/) is a protocol for sending and receiving money in any pair of currencies.

With the Artemis Payment Gateway for Wordpress (WooCommerce), you can accept payment for orders in your Wordpress (WooCommerce) store using the Stellar protocol (and currency).

After installing the plug-in, you will be able to sell in any currency which your Stellar account can accept and is available on Artemis Payment Gateway.

The Stellar protocol also has a built in currency, named Stellar, with the currency code **XLM**. The Artemis Payment Gateway plugin adds **XLM** as an option for your store's currency.


#### Demo Store 

Want to try it out?

[Artemis Demo](https://demo.artemis-gateway.com).

#### Contribute 

Want to get involved with the Artemis Payment Gateway plug-in development, join us on [GitHub](http://github.com/artemis-gateway/woocommerce-stellar).

#### Installation

**Installation via WordPress plugin installer [Click Here](https://wordpress.org/plugins/artemis-payment-gateway)**

1. Go to: Plugins > Add New.
2. Type “artemis payment gateway” in to the search box and hit enter.
3. Click the “Install” button.
4. Activate as you would any other WordPress plugin.

**Manually via SFTP**
1. Upload the plugin's files to the `/wp-content/plugins/` directory
2. Activate the plugin through the **Plugins** menu in WordPress
3. Visit the **WooCommerce > Settings > Payment >
4. Select **Enable ARTEMIS PAYMENT GATEWAY**.
5. Select **Manage**
6. Enter your Stellar Address

You're ready to start selling via Stellar!


#### FAQs 

#### What currencies can I accept via ARTEMIS PAYMENT GATEWAY? 

Any supported token. For an updated list please visit 
[Artemis-Gateway.com](https://artemis-gateway.com/supported-tokens/).

Don’t see a token you want to accept as payment. You can add a token. To get started goto [Artemis-Gateway.com](https://artemis-gateway.com/add-token/).

Your token will be added to the system and all users of Artemis Payment Gateway everywhere will be able to accept and pay with your tokens.

#### Why doesn’t my product show a token?

Make sure you set the price for each token you want to accept. It will then appear at check out.

#### How can I add new currencies to my Stellar account? 

You can use a third party wallet to simplify the process like [LOBSTR](https://lobstr.co)

1. Login to your [Lobstr Account](https://lobstr.co)
2. Click  **add asset**
3. Enter the full URL, Issuer Public Key, or asset name.
4. Add the token to your account

Or You can add new currencies to your account using the official [Stellar Account Viewer](https://accountviewer.stellar.org/#!/).


#### How can I sell with Stellar from multiple WooCommerce Stores? 

It’s east, just memo prefix them for different stores (e.g. `STORE1-1235` or `STORE2-2866`).
WooCommerce > Settings >Payments>Then add the Memo Prefix


#### Does the plug-in ask for my Secret Key.

No, All you will need is your public key where you want the payment sent to. 

Make sure you use an account that does not require a memo to receive the payments. 

If you use A wallet like Coinbase your funds will be lost.

You can set up a free account at [LOBSTR](https://lobstr.co) to receive payments.

#### I'm having trouble, where can I get help?

If you've found a bug in the plug-in or have a feature request, please [open a new issue](https://github.com/artemis-gateway/woocommerce-stellar/issues/new) on the [Artemis Payment Gateway GitHub Repository](https://github.com/artemis-gateway/woocommerce-stellar/).

### License

The Artemis Payment Gateway to accept stellar payments  is released under the [GPLv3](http://www.gnu.org/licenses/gpl-3.0.html) license.

>>>> Copyright (C) 2022 Artemis Gateway
