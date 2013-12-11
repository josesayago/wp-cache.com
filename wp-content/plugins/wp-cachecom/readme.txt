=== WP-Cache.com ===
Contributors: phatjay
Tags: cache, wp cache, caching, wp super cache, w3tc
Requires at least: 3.3
Tested up to: 3.8.1
Stable tag: 4.8
License: GNU GPL 3.0
License URI: http://www.gnu.org/licenses/gpl.html

The easiest, fastest, most light-weight WordPress Cache plugin available.

== Description ==

<a target="_blank" href="http://wp-cache.com/">WP-Cache.com</a>, the easiest and fastest WordPress Cache plugin. WP-Cache.com, it just works! 

This project is maintained on <a target="_blank" href="https://github.com/icryptic/WP-Cache.com">Github</a>.

== Installation ==

This will activate the WP-Cache.com WordPress Plugin.

1. Upload `wp-qore` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Adjust options within 'WP-Cache.com' admin menu

Once activated, please update your options via the WP-Cache.com menu located within the left side of your wp-admin.

== Frequently Asked Questions ==

= How do I know if the plugin is working?  =

Once you have turned 'On' Frontend Caching from the WP-Cache.com menu within your wp-admin, you simple can log out of WordPress and head on over to your frontend. Once there, just refresh the page, then look at the source code of your homepage. You will see at the very end of the source code just below the closing </html> tag a comment indicating that WP-Cache.com generated the page from cache. 

= Does WP-Cache.com cache the wp-admin backend?  =

No. WP-Cache.com does not cache the wp-admin backend. In fact, WP-Cache.com doesnt even serve cached files to the admin.

== Changelog ==

= 1.0.3 =
* Fixed minor bug on line 163 of functions.php involving a double spaced underscore.

= 1.0.2 =
* Added localization support (Contributed by: Kenth Hagström via by https://github.com/keha76 )

= 1.0.1 =
* Renamed function in index.php to avoid conflict.

= 1.0.0 =
* Initial Release

== Upgrade Notice ==

= 1.0.3 =
* Upgrade to fix minor bug

= 1.0.2 =
* Upgrade to latest release

= 1.0.1 =
* Upgrade to latest release
