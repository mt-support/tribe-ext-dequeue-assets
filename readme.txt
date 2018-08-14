=== Tribe Extension: Dequeue Assets ===
Contributors: ModernTribe
Donate link: http://m.tri.be/29
Tags: events, calendar
Requires at least: 4.5
Tested up to: 4.9.8
Requires PHP: 5.6
Stable tag: 1.0.4
License: GPL version 3 or any later version
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Dequeues any scripts or styles that are registered using the `tribe_asset()` function.

== Description ==

Dequeues any scripts or styles that are registered using the `tribe_asset()` function. Adds a list of dequeueable assets to WP Admin > Events > Settings.

== Installation ==

Install and activate like any other plugin!

* You can upload the plugin zip file via the *Plugins ‣ Add New* screen
* You can unzip the plugin and then upload to your plugin directory (typically _wp-content/plugins)_ via FTP
* Once it has been installed or uploaded, simply visit the main plugin list and activate it

== Frequently Asked Questions ==

= Where can I find more extensions? =

Please visit our [extension library](https://theeventscalendar.com/extensions/) to learn about our complete range of
extensions for The Events Calendar and its associated plugins.

= What if I experience problems? =

We're always interested in your feedback and our [premium forums](https://theeventscalendar.com/support-forums/) are the
best place to flag any issues. Do note, however, that the degree of support we provide for extensions like this one
tends to be very limited.

== Changelog ==

= [1.0.4] 2018-08 =

* Fix - Updated to support the new way of loading assets, [as of the July 29, 2018, products updates](https://theeventscalendar.com/maintenance-release-for-the-week-29-july-2018/)
* Fix - Strings are now translatable
* Tweak - License changed from GPLv2+ to GPLv3+
* Tweak - Plugin header added support for GitHub Updater

= [1.0.3] =

* Fix – Extension now conditionally requires the Settings_Helper.php file to prevent the "Cannot declare class Tribe__Extension__Settings_Helper because the name is already in use" error.

= [1.0.2] =

* Fix – An error that occurred upon first activating the extension.

= [1.0.1] =

* Fix – An error "Cannot redeclare class" that happened when multiple extensions were active.
* Tweak – Moved `View_Helper` to the Extension namespace.

= [1.0.0] =

* Initial release