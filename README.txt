=== Ktai Location ===
Contributors: IKEDA Yuriko (lilyfan)
Tags: mobile, location, geo, geography, gps, exif
Requires at least: 2.7
Tested up to: 3.2.1
Stable tag: 1.1.1

"Ktai Location" extracts geographic data (latitude, longitude) from your post and save them as "Lat_Long" custom fields.

== Description ==

"Ktai Location" extracts geographic data (latitude, longitude) from your post in many ways: 

* EXIF of JPEG/TIFF images
* map service URLs in post content
* address or place name in `[geo]` shortcodes

And the plugin save them as "Lat_Long" custom fields.
To use geographic data, you need to use other plugins that can read the custom fields.
Below plugins can deal "Lat_Long" custom fields:

* [Lightweight Google Maps](http://wppluginsj.sourceforge.jp/lightweight-google-maps/)
* [Google Maps Anywhere](http://wordpress.org/extend/plugins/google-maps-anywhere/)

Available map services and URL formats:

* EZ Naviwalk
* NTT docomo GPS
* Mobile Yahoo! Map
* NAVITIME
* Zenrin
* MapFan
* Ekitan
* Mapion
* Mapple
* Chizumaru

== Requirements ==

* WordPress 2.7 or later
* PHP 4.3 or later
* EXIF module for PHP
* Google Maps API Key (if you convert address from `[geo]` shortcode)

== Installation ==

"Ktai Location" can be installed in 2 steps:

	1. Unzip "ktai-locaion.N.N.N.zip" archive and put the ktai-location folder into your "plugins" directory (wp-content/plugins/) of the server.
	2. Activate the plugin.

	If you want to use geocoding (converting `[geo]` shortcodes into latitude/longtitude)
	do below steps.

	3. Login to your wordpress admin panel, open "Ktai Location" configuration panel.
	4. Type your Google Maps API Key to the admin panel. If you don't have one, sign up at Google.

== Licence ==

The license of this plugin is GPL v2.

== Restrictions ==

* Reading EXIF feature needs to locate the images at the same server to this plugin. Citing URL of a remote server (such as Flickr, Picasa, etc) are not usable.

== Getting a support ==

To get support for this plugin, please send an email to ikeda.yuriko+ktailocation _@_ GMAIL COM. (You need adjust to valid address)

== Frequently Asked Questions ==

== Changelog ==
= 1.1.1 (2011-08-31) =
* Fixed the plugin config panel.
* Fixed Geocoding feature.

= 1.1.0 (2011-08-31) =
* Hosted to wordpress.org/extend/plugins
* Create admin panel to input Google Maps API Key.
* Localized plugin description.
* Reading EXIF GPS is now available at WordPress multisite.
* Fixed HTML syntax error when wrapping location URL for mobile.
* Fixed duplicating Lat_Long custom fields when editing a post.

-- snip --
= 0.7.0 (2007-01-18) =
* Initial version
