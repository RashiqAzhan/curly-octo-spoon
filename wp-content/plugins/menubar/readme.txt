=== Menubar ===
Contributors: dontdream
Tags: menu, menubar, navigation, suckerfish, superfish
Requires at least: 4.9
Tested up to: 5.7
Stable tag: 5.7.2

Single and multi-level menus for your WordPress site, styled with customizable menu templates.

== Description ==

With Menubar you can easily build and manage single and multi-level menus for your WordPress site.

* Build your menus selecting item types among Home, FrontPage, Heading, Tag, TagList, Category, CategoryTree, Page, PageTree, Post, SearchBox, External, PHP, Custom, in any combination

* Display a menu inserting in your theme, e.g. at the end of *header.php*, the following line:<br><code><?php do_action ('menubar', 'name of your menu'); ?></code>

* Use the *Menubar* widget to display a menu in a sidebar or widget area

* Use the shortcode <code>[menubar menu='name of your menu']</code> to display a menu in a post or page, or in a page builder text block

* To style your menus, select one of the default Menubar templates, customize your selected template, or use the CSS from your theme

* Customized Menubar templates can be moved into an independent folder, so you can upgrade to a new Menubar version without losing your changes

A detailed documentation is available on the plugin's site, see for instance [Menubar](http://www.dontdream.it/menubar/), and [The Menubar PHP type](http://dontdream.it/menubar/the-menubar-php-type/) tutorial.

== Installation ==

Follow the standard plugin installation procedure, see [Managing Plugins](https://wordpress.org/support/article/managing-plugins/#installing-plugins).

== Changelog ==

= 5.7.2 =
* Upgraded Superfish (by Joel Birch) to v1.7.10 
* No longer requires the *Enable jQuery Migrate Helper* plugin
= 5.7.1 =
* Fixed two PHP 7.4 Notices
= 5.7 =
* Requires [Enable jQuery Migrate Helper](https://wordpress.org/plugins/enable-jquery-migrate-helper/) with WordPress 5.5
= 5.6.5 =
* Fixed a few PHP 7 Warnings
= 5.6.4 =
* Improved the Menubar widget
* Fixed a few PHP Notices when deleting a menu
= 5.6.3 =
* Removed trailing spaces from menu names
= 5.6.2 =
* Updated for PHP 7
= 5.6.1 =
* Improved the usability of the *PHP* menu item type
= 5.6 =
* Added shortcode to display a menu in a post or page, or in a page builder text block
* Added the plugin icon - thanks to Sebastian Rubio
= 5.5 =
* Updated to use WP language packs
= 5.4 =
* Updated for WordPress 4.3
= 5.3 =
* Code cleanup to remove a number of PHP Notices
= 5.2 =
* Fixed two more PHP Warnings: Creating default object from empty value
= 5.1 =
* Fixed two PHP 5.4 Warnings: Creating default object from empty value
= 5.0 =
* All the default Menubar templates are now included in the plugin folder, so you don't have to download them separately
= 4.10 =
* Fixed a compatibility bug with the qTranslate plugin
= 4.9 =
* Enhanced the PHP item type, so you can dynamically generate both label and link of a menu item
* Fixed a bug that prevented highlighting in the External and PHP types when a querystring was present
= 4.8 =
* Added the PHP item type, so you can build your menu items dynamically with PHP code
= 4.7 =
* Added the Exclude field to PageTree and CategoryTree types, so you can prevent one or more elements from being displayed 
* Added the Headings field to PageTree and CategoryTree types, so you can make one or more elements non clickable 
= 4.6 =
* Added the Tag and TagList types (only with new template versions)
* Added the Depth field to PageTree and CategoryTree types, so you can choose how many tree levels to display 
= 4.5 =
* Added support for icons in menu items (only with new templates)
* Fixed a bug affecting single and double quote characters that were incorrectly escaped 
= 4.4 =
* Improved performance moving the Menubar data from a DB table to a serialized option, so just a single DB call per page is needed
= 4.3 =
* Fixed a bug affecting the *Add Menu Item* and *Edit Menu Item* forms in IE6 and IE7
= 4.2 =
* Added support for the wp-config.php FORCE\_SSL\_ADMIN option
* Added support for the new Superfish template
= 4.1 =
* Improvements to the new template structure - older templates are supported as well
* Added the Custom type to insert custom HTML in your menu (only with new templates)
* The name of a menu item is automatically generated when the *Name* field is left blank (only with new templates)
= 4.0 =
* New template structure for better customization - old templates are supported as well
* Added the SearchBox type to integrate a search box in your menubar (only with new templates)
* Moved the *Menubar* admin page under the *Appearance* admin menu
= 3.6 =
* Improved the first installation procedure with more user-friendly messages
= 3.5 =
* Added the *Menubar* widget to display a menu in a sidebar or widget area
= 3.4 =
* Improved compatibility with the qTranslate plugin
= 3.3 =
* Fixed a bug affecting menu names containing a space, and a bug in a special menu reordering case
= 3.2 =
* Added more options to easily rearrange the order of your menu items
= 3.1 =
* Menubar templates are now stored in the *menubar-templates* folder, so future automatic upgrades won't overwrite your template customizations
= 3.0 =
* First version hosted in the WordPress Plugin Directory
