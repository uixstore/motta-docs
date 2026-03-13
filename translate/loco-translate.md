# Using Loco Translate Plugin

The easiest way to translate your theme is using the Loco Translate plugin.

1. Go to **Plugins > Add New**
1. Search for plugin “Loco Translate”
1. Install and Activate the plugin.
1. After Activation locate **Loco Translate**

Loco Translate plugin has it own a short tutorial for beginner. Please take a look at it [here](https://localise.biz/wordpress/plugin/beginners).


## Translate Motta Theme

1. Navigate to **Loco Translate > Themes** and select **Motta** in the theme list to start translating.

1. Click on **New Language** link to add new translation for Motta.

	<!-- ![Loco Translate new language](_images/translate--loco_add.png) -->

1. Select language the language.

1. Chose the location to store your translation files in **languages/themes** foler.

	<!-- ![Loco Translate select language](_images/translate--loco_select.png) -->

1. Click **Start Translating** button to start translating Motta theme.

1. On the next screen all the English text strings that are inside the theme will be listed. Select text string from the **Source Text** list and then add your translation for it in the textarea below.

	<!-- ![Loco Translate translate](_images/translate--loco_translate.png) -->

1. Then click the **Save** button from top and all your translated text should appear on the your website instead of the default English text.


## Translate Plugins

There are some plugins which is included in Motta need to be translated.

1. Motta Addons
1. WooCommerce

The translation process for plugins is the same translating a theme:

1. Navigate to **Loco Translate > Plugins** and select the plugin you want to translate in the plugins list to start translating.
1. Click on **New Language** link to add new translation for it.
1. Select language the language.
1. Chose the location to store your translation files in **languages/plugins** foler.
1. Click **Start Translating** button to start translating select plugin.
1. On the next screen all the English text strings that are inside the plugin will be listed. Select text string from the **Source Text** list and then add your translation for it in the textarea below.
1. Then click the **Save** button from top and all your translated text should appear on the your website instead of the default English text.

## Can't Translate Some Strings

When WordPress updates the theme in future you may find your translations no longer correspond to the English text in the theme. Loco Translate won’t automatically fix this for you. That’s why you’ll have to update your custom translations manually when the theme has been updated.

WordPress should automatically update the original System translations whenever it updates the theme, but check that’s working before proceeding with the next step. You can download them yourself if you need to.

Here is the guideline to fix the problem

1. Go to **Loco Translate > Settings > Extracting strings** and enter Skip PHP files larger than is 500K and click Save button
2. Go to **Loco Translate > Theme/Plugin > Edit Template**.
3. Click **Sync** button > click **Save** button.
4. Go to **Loco Translate > Theme/Plugin > edit your language**.
5. Click **Sync** button
6. Find the text and translate it > click **Save** button.