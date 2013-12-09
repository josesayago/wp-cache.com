=== WP Qore ===
Contributors: phatjay
Tags: developer, security, performance, antivirus, virus, malware, cache, tools, qore, core
Requires at least: 3.3
Tested up to: 3.8.1
Stable tag: 4.8
License: GNU GPL 3.0
License URI: http://www.gnu.org/licenses/gpl.html

WordPress Security, Developer Tools Plugin.

== Description ==

<a target="_blank" href="http://wpqore.com/">WP Qore</a>, a plugin that provides additional security, performance functionality, and developer tools that can be turned on or off at any time. WP Qore, first debut in the WordPress.org plugin repository is v1.1.4 and previous versions are maintained on <a target="_blank" href="https://github.com/icryptic/wp-qore/">Github</a>.

Available Options: (toggle on/off)

* customize login page
* force wp-admin ssl
* hide login page
* security advisor
* replace dashboard
* disable nag updates
* disable core updates
* admin bar removal
* collapse admin menu
* frontend caching
* use jquery cdn
* shortcode in widget
* php in widgets
* import/export widgets
* remove wp version
* minify your html
* gzip compression
* cleanup wp meta
* new theme directory
* unique source code

== Installation ==

This will activate the WP Qore WordPress Plugin.

1. Upload `wp-qore` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Adjust options within 'WP Qore' admin menu

Once activated, please update your options via the WP Qore menu located within the left side of the wp-admin.

== Frequently Asked Questions ==

= How do you see this plugin differentiating itself from others like Better WP Security, Hide My Login, or W3TC?  =

I can't say this plugin compares with the others. It wasn't created to compete with others. Truthfully, this plugin was created for myself. The functionality the plugin provides I use often with my own and even client sites. So I basically created a lightweight plugin that would serve the purpose of a way to turn on and off certain functionality preferably security and performance related things.

= Do you have a Github repository, too? =

Yes. I currently have WP Qore on Github. You may find the project here: https://github.com/icryptic/wp-qore

== Changelog ==

= 1.4.2 =
* Added WP Qore to admin bar.

= 1.4.1 =
* Added option to keep wp-admin menu folded.

= 1.4.0 =
* Added Cache Assistance tab to dashboard.
* Removed gzip option. Already handled by cache.

= 1.3.9 =
* Added frontend caching system.

= 1.3.8 =
* Replaced deprectaed function in Database Audit.
* Removed prepare() from 2 lines within the functions.php file.
* Resolved all debug notices.

= 1.3.7 =
* Removed load_plugin_lang in sec-advisor.php.

= 1.3.6 =
* Added activation and deactivation hook to index.php.

= 1.3.5 =
* Updated settings.php

= 1.3.4 =
* Added example screenshot to the WP Qore settings panel for Dashboard Tabs.

= 1.3.3 =
* Added option to WP Qore settings panel to conceal the WP Qore tabs from within the dashboard_view.php.

= 1.3.2 =
* Added tabs to dashboard_view.php.

= 1.3.1 =
* Minor changes. Cleaned up sec-advisor.php file.

= 1.3.0 =
* Added Security Advisor. Security Advisor offers you protection from security threats, such as: virus, malicious code, and security exploits.

= 1.2.0 =
* Bug in commit for 1.1.9 caused core-update.php to not reach the wp repo. This update is to solve that issue.

= 1.1.9 =
* Settings.php UI update.

= 1.1.8 =
* Added option to disable core updates. Used for dev sites.
* Fixed spelling typo within settings.php.
* Added option to disable post revisions.
* Added option to force wp-admin ssl connection.

= 1.1.7 =
* Replaced CSS import with enqueue for both dashboard and WP Qore admin options page.

= 1.1.6 =
* Removed dashboard icon opacity css.
* Added push button effect css to dashboard icons.

= 1.1.5 =
* Replaced dashboard icons.
* Fixed dashboard css (adjusted icon opacity).

= 1.1.4 =
* Debut version in WordPress.org plugin repository.

= 1.1.3 =
* Deprecated submenu item > login-security.php. 

= 1.1.2 =
* Deprecated WordPress Admin Bootstrap.

= 1.1.1 =
* Replaced checkboxes with on/off toggle buttons.

= 1.1.0 =
* Moved import/export widgets to the wp-admin > Tools menu via add_admin_menus().

= 1.0.9 =
* Updated code to use prepare() with queries to protect them from sql injections.

= 1.0.8 =
* Visual fix. Added two line breaks on db audit panel.

= 1.0.7 =
* Disabled calling wp-load directly on line 4.

= 1.0.6 =
* Replaced deprecated function in functions.php, has_cap to manage_options.

= 1.0.5 =
* Fixed minor bug with import/export widgets

= 1.0.4 =
* Enabled import and exporting of widgets. 
* Fixed small bug in functions.php pertaining to if{shortcode}.

= 1.0.3 =
* Enabled php in widgets. 
* Updated project description.

= 1.0.2 =
* Deprecated self-hosted plugin updater in preparation for the WordPress.org repository.

= 1.0.1 =
* Fixed a bug in updater. This was pre-wp repo.

= 1.0 =
* Initial Release

== Upgrade Notice ==

= 1.4.2 =
* Upgrade for the latest version.

= 1.4.1 =
* Upgrade for the latest version.

= 1.4.0 =
* Upgrade for the latest version.

= 1.3.9 =
* Upgrade for the latest version.

= 1.3.8 =
* Upgrade for the latest version.

= 1.3.7 =
* Upgrade for the latest version.

= 1.3.6 =
* Upgrade for the latest version.

= 1.3.5 =
* Upgrade for the latest version.

= 1.3.4 =
* Upgrade for the latest version.

= 1.3.3 =
* Upgrade for the latest version.

= 1.3.2 =
* Upgrade for the latest version.

= 1.3.1 =
* Upgrade for the latest version.

= 1.3.0 =
* Upgrade for the latest version.

= 1.2.0 =
* Upgrade for the latest version.

= 1.1.9 =
* Upgrade for the latest version.


= 1.1.8 =
* Upgrade for the latest version.

= 1.1.7 =
* Upgrade for the latest version.

= 1.1.6 =
* Upgrade for the latest version.

= 1.1.5 =
* Upgrade for the latest version.

= 1.1.4 =
* Upgrade for the latest version.

= 1.1.3 =
* Upgrade to fix possible security vulnerbility.

= 1.1.2 =
* Upgrade to fix possible security vulnerbility.

= 1.1.1 =
* Upgrade to add cosmetic changes.

= 1.1.0 =
* Upgrade to fix minor bug in export widgets.

= 1.0.9 =
* Upgrade to fix possible security vulnerbility.

= 1.0.8 =
* Fix to Database Optimization Audit panel.

= 1.0.7 =
* Upgrade to fix possible security vulnerbility.

= 1.0.6 =
* Upgrade to fix deprecated function in functions.php.

= 1.0.5 =
* Upgrade to fix minor bug with import/export widgets.

= 1.0.4 =
* Upgrade adds new functionality.

= 1.0.3 =
* Upgrade adds new functionality.

= 1.0.2 =
* Upgrade now for the latest version.

= 1.0.1 =
* Upgrade now to make sure you do not miss any future updates. This update fixes the WordPress updater to notify users upon new version upgrades.
