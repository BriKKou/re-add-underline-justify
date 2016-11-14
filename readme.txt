=== Re-add text underline and justify ===
Contributors: briKou
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7Z6YVM63739Y8
Tags: mce, editor, underline, justify, tinyMCE, 4.7, wysiwyg, visual editor
Requires at least: 4.7
Tested up to: 4.7
Stable tag: 0.1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
 
This tiny plugin re-adds the Editor text underline, text justify and rearrange buttons in the WYSIWYG as they were before WordPress 4.7.


== Description ==

In WordPress 4.7, the core developper team decided to make various changes in the editor (TinyMce WYSIWYG), including removing the **underline and justify buttons** and rearranging some of the toolbar buttons.
If you don't want to change the way you edit your content and/or don't want to confuse your customers with a new contribution interface, this very lightweight plugin will set the editor style back to its previous state (like in WordPress 4.6 and above versions).

**You may change the Editor style from the Writing option page.**

3 options are available for the Editor style :

* Default - without underline & justify buttons
* Re-add underline & justify buttons
* Re-add underline & justify + rearrange

In my opinion, the third option is a fair compromise between versions 4.6 and 4.7 of the editor. It moves up the style select to the first line, and moves the underline button after the other text position buttons.


[DOCUMENTATION](http://b-website.com/re-add-text-underline-and-justify "Plugin documentation")

[CHECK OUT MY OTHER PLUGINS](http://b-website.com/category/plugins-en "More plugins by b*web")


**Please ask for help or report bugs if anything goes wrong. It is the best way to make the community benefit!**


== Installation ==

1. Upload and activate the plugin (or install it through the WP admin console)
2. Go to Settings -> Writing and select the option you want under "Editor style".
3. That's it, it is ready to use!

== Frequently Asked Questions ==

= Where can I change the Editor style? =
Just go to Settings -> Writing and select the option you want under "Editor style".


== Screenshots ==

1. Change the Editor style from the Writing option page
2. Default - without underline & justify buttons
3. Re-add underline & justify buttons
4. Re-add underline & justify + rearrange


== Changelog ==

= 0.1.2 - 11/14/2016 =
* Change mce button hook priority to prevent errors with other plugins adding extra buttons
* readme.txt update

= 0.1.1 - 11/10/2016 =
* Fix an issue hidding Editor content.

= 0.1 - 11/06/2016 =
* First release.

== Upgrade Notice ==

= 0.1 =
* First release.