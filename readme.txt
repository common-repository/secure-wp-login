=== Secure wp-login.php ===

Contributors:      Neil Patel, WPBuild Beginner Team
Tags:              Secure, login, wp-login, wp-login.php, custom login url, rename, change, Remove, Secure,
Requires at least: 4.9.6
Tested up to:      4.4.1
Stable tag:        2.5.5
License:           GPL-3.0+

Change wp-login.php to anything you want.

== Description ==

** Secure-wp-login offer support through the support forum. Use [Website](https://www.wpbuild.me/secure-wp-login/ instead.**

*Secure wp-login.php* is a very light plugin that lets you easily and safely change,Remove Old wp-login.php to anything you want. 

= Compatibility =

All login related things such as the registration form, lost password form, login widget and expired sessions just keep working.

It’s also compatible with any plugin that hooks in the login form, including

* BuddyPress,
* Woocommerce,
* TML,
* UserPro,
* bbPress,
* Limit Login Attempts,
* and User Switching.

Obviously it doesn’t work with plugins that *hardcoded* wp-login.php.

Works with multisite, but not tested with subdomains. Activating it for a network allows you to set a networkwide default. Individual sites can still Secure their login page to something else.

If you’re using a **page caching plugin** you should add the slug of the new login url to the list of pages not to cache.

If you wish, you can block wp-login.php with `.htaccess` from now on.

== Installation ==

1. Go to Plugins › Add New.
2. Search for *Secure wp-login.php*.
3. Look for this plugin, download and activate it.
4. The page will redirect you to the settings. Secure wp-login.php there.
5. You can change this option any time you want, just go back to Settings › Permalinks › Secure wp-login.php.

or 

1. Go to https://www.wpbuild.me/secure-wp-login/download
2. Go to Plugins > Add New > Upload Your File
3. Activating
4.You can change this option any time you want, just go back to Settings › Permalinks › Secure wp-login.php.

== Frequently Asked Questions ==

= I forgot my login url!  =

Either go to your MySQL database and look for the value of `rwl_page` in the options table, or remove the `Secure-wp-login` folder from your `plugins` folder, log in through wp-login.php and reinstall the plugin.

On a multisite install the `rwl_page` option will be in the sitemeta table, if there is no such option in the options table.

= How do i Remove Secure WP Login Plugins
1. Go to Your cPanel > File Manage
2. wp-content > Plugin > Secure-wp-login
3. Remove the Folder
 
== Changelog ==

= 1.0 =

* Initial version.
