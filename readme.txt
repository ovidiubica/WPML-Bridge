=== AppThemes WPML Bridge ===
Contributors: appthemes
Tags: appthemes, wpml, integration, language, localization, multilingual, classipress
Requires at least: 4.0
Tested up to: 4.6.1
Stable tag: 1.3

This plugin adds additional WPML compatibility for AppThemes themes.

== Description ==

When it comes to creating a multilingual website with WordPress, there's no question that the [WPML plugin](http://wpml.org/) is the best out there.
This plugin handles all the little details required to run AppThemes themes together with WPML.

Find out more at [plugin page](http://docs.appthemes.com/wpml-bridge-plugin/)

= Supported themes =
* ClassiPress

Support for other themes coming soon.

== Installation ==

Manual installation via FTP:

1. Upload the `appthemes-wpml-bridge` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' screen in your WordPress admin area


== Upgrade Notice ==


== Frequently Asked Questions ==

= Plugin doesn't work for me, what to do? =

Report it with details on [AppThemes support forum](http://forums.appthemes.com/plugins/).


== Screenshots ==



== Changelog ==

= 1.3 =

* Use new function cp_explode() to properly handle checkbox values
* Register in WPML also escaped checkbox values
* Corrected loading plugin textdomain
* Fix typo in variable name

= 1.2 =

* Make all fields labels and values translatable on the single ClassiPress Ad page

= 1.1 =

* Added immediate registering strings for form fields
* Added localization of dropdown, radio, and checkbox values
* Added all categories to form layout editor
* Fixed featured ads slider and marking ad as featured
* Fixed language selector for frontend Edit Ad page
* Minor corrections to Orders

= 1.0 =

* Initial release
