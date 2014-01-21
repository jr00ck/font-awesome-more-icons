font-awesome-more-icons
=======================

Easily use the Font Awesome icons in WordPress but with MORE icons and MORE features using HTML, shortcodes, or TinyMCE plugin.

Font Awesome More (Fontstrap) provides easy use of all icons from the [Font Awesome](http://fortawesome.github.io/Font-Awesome/) set, but with [MORE icons](http://blog.webguysaz.com/font-awesome-more-fontstrap-icon-additions/) from the [Fontstrap](http://gregoryloucas.github.io/Font-Awesome-More/) extension set and with MORE features. The icons are infinitely scalable and screen reader compatible.

A full list of all 400+ icons is available here:

[Font Awesome icons](http://fortawesome.github.io/Font-Awesome/icons/)  
[Font Awesome More (Fontstrap) icons](http://blog.webguysaz.com/font-awesome-more-icon-list-plugin-version-3-3/)

To use any of the Font Awesome More icons on your WordPress site you have three options:

= HTML Option =

All code examples on the Font Awesome site apply: [http://gregoryloucas.github.io/Font-Awesome-More/#examples](http://gregoryloucas.github.io/Font-Awesome-More/#examples)

**Examples**

WordPress icon <i class="icon-wordpress"></i>

`<i class="icon-wordpress"></i>`

Google icon 2x size

`<i class="icon-google icon-2x"></i>`

Google Chrome icon large size

`<i class="icon-chrome icon-large"></i>`

= Shortcode Option =

Don't want to worry about HTML tags?  You can use a shortcode in your posts, pages and even widgets to display a Font Awesome More icon.

*Note:* In my plugin (as of 3.5), the "icon-" prefix is no longer needed in shortcode attributes. This is in preperation for the [Font Awesome 4.0](http://blog.fontawesome.io/2013/06/04/upcoming-changes-in-font-awesome-3.2-and-4.0/) release that will change the prefixes. Therefore, I highly recommend that you only use the shortcode options for icons, and not HTML, so that the plugin can handle the prefixes for you and your icons will not break when Font Awesome 4.0 comes out.


WordPress icon

`[icon name=wordpress]`

Google icon 2x size

`[icon name=google size=2x]`

Google Chrome icon with title and no space after icon

`[icon name=chrome title="Google Chrome" space=false]`

PayPal icon using shortcode within PHP instead of using the HTML option (e.g. within your theme/template files)

`<?php echo do_shortcode('[icon name=paypal]'); ?>`

= New Shortcode Options since 3.5 =

Now you can turn off the automatic spacing after an icon with "space=false". See screenshots for an example of results.

In preperation for [Font Awesome 4.0](http://blog.fontawesome.io/2013/06/04/upcoming-changes-in-font-awesome-3.2-and-4.0/), you can also leave off the "icon-" prefix on your shortcode options, as that prefix will be changing. The plugin will automatically add the appropriate prefix for you.

Evernote icon with no trailing space (note no "icon-" prefix)

`[icon name=evernote space=false]`

= New Shortcode Options since 3.4 =

Now you can easily set the size and a title/alt text to icons within shortcodes. Size options are large, 2x, 3x, or 4x.


WordPress icon (large size)

`[icon name="wordpress" size="large"]`

Google icon (3x size)

`[icon name="google" size="3x"]`

Google Chrome icon (4x size with title text)

`[icon name="chrome" size="4x" title="Use Google Chrome"]`


= Credits =

* The Font Awesome & Font Awesome More (Fontstrap) font is licensed under the [SIL Open Font License](http://scripts.sil.org/OFL).

* Font Awesome & Font Awesome More (Fontstrap) CSS, LESS, and SASS files are licensed under the [MIT License](http://opensource.org/licenses/mit-license.html).

* The Font Awesome & Font Awesome More (Fontstrap) pictograms are licensed under the [CC BY 3.0 License](http://creativecommons.org/licenses/by/3.0/).

* [Font Awesome](http://fortawesome.github.com/Font-Awesome) is a product by Dave Gandy

* [Font Awesome More](http://gregoryloucas.github.io/Font-Awesome-More/) (Fontstrap) is a product of Gregory Loucas.

* The rights to each pictogram in the social and corporate extensions are either trademarked or copyrighted by the respective company.

* This plugin is based off of [Font Awesome Icons](http://rachelbaker.me/font-awesome-icons-wordpress-plugins/) by Rachel Baker.

= Author =

*   [Web Guys](http://webguysaz.com)

= Icons =

[Font Awesome icons](http://fortawesome.github.io/Font-Awesome/icons/)  
[Font Awesome More (Fontstrap) icons](http://blog.webguysaz.com/font-awesome-more-fontstrap-icon-additions/)