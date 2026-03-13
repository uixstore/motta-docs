# WooCommerce Pages

Upon installation, WooCommerce creates the following new pages via the [Setup Wizard](https://woocommerce.com/document/woocommerce-setup-wizard/):

- **Shop** – No content required.
- **Cart** – Contains [woocommerce_cart] shortcode and shows the cart contents
- **Checkout** – Contains [woocommerce_checkout] shortcode and shows information such as shipping and payment options
- **My Account** – Contains [woocommerce_my_account] shortcode and shows each customer information related to their account, orders, etc.

## Install pages again

If you skipped the Setup Wizard or want to install missing WooCommerce pages, go to **WooCommerce > Status > Tools** and use the page installer tool.

![](_images/woo_pages.png)

<hr>

## Tell WooCommerce what pages to use

If you set up new pages yourself, or want to change what pages are used for things like cart and checkout, you need to tell WooCommerce which pages to use.

To tell WooCommerce what pages to use for Cart, Checkout, My Account, and Terms and Conditions, go to **WooCommerce > Settings > Advanced.**

![](_images/woo_pages_1.png)

To tell WooCommerce what pages to use for the Shop page go to **WooCommerce > Settings > Products.**

![](_images/woo_pages_2.png)

<hr>

## What is the Shop page?

The Shop page is a placeholder for a [post type archive](https://codex.wordpress.org/Function_Reference/is_post_type_archive) for products. It may render differently than other pages in your install.

If you’re using SEO plugins, they may include settings specific to custom post type archives, and these settings are what you should be using to control the shop page.
