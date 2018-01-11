=== Google Map Targeting ===
Contributors: RealMag777
Donate link: https://codecanyon.net/user/realmag777/portfolio?ref=realmag777
Tags: google map, google, map, post, page, shortcode
Requires at least: 3.5.0
Tested up to: 4.9
Stable tag: 1.1.6

Set Google Map everywhere by shortcode on your WordPress site simply. One click - one map! This lightweight plugin is managed in an intuitive way.

== Description ==

Set google map on your WordPress site using shortcode or widget by one click. 
Interactive map mode, image map mode, any maps sizes, very pleasant and convenient popup window with all 
map options. You can set map as by latitude and longitude so by address. One place - one click, do not waste 
time walking to other pages.

The plugin has in-built widget for placing maps into sidebars.

Example of the shortcode: 
<code>
[gmap_targeting height="500" width="500" mode="map" location_mode="address" latitude="" longitude="" address="Spain, Alicante, castell de la santa barbara" zoom="14" maptype="ROADMAP" enable_marker="1" enable_scrollwheel="1" marker_is_draggable="0" enable_popup="1"]Hello World!![/gmap_targeting]
</code>


https://www.youtube.com/watch?v=SAiS3QtaUWU

== Installation ==

= New Installations =
* Download to your plugin directory or simply install via Wordpress admin interface.
* Activate.
* Use.

== Frequently Asked Questions ==

Q: Demo ...?
R: [https://pluginus.net/shop/wordpress-plugins/google-map-targeting/](https://pluginus.net/shop/wordpress-plugins/google-map-targeting/)

Q: How to enable Google Map API only on some pages
R: In your current wp theme functions.php file use next code:
<code>
add_filter('google_map_pages',function($pages){
    return array(402,407);
},999);
</code>

Q: How to set image width in '%' instead of 'px'
R: Just write in field 'width' of shortcode value with '%' sign. For example: 30%

== Screenshots ==

1. Shortcode button on editor
2. Shortcode popup
3. Plugins widget

== Changelog ==

= 1.1.6 =
* 1 notice fixed
* enabling CURL functionality if on the server allow_url_fopen=0

= 1.1.5 =
WordPres 4.6 compatibility

= 1.1.4 =
WordPres 4.3 compatibility

= 1.1.3 =
WordPres 4.0 compatibility

= 1.1.2 =
Russian language files added. All harcoded words are translate able. Some improvements in shortcode popup with the jquery.

= 1.1.1 =
WordPress 3.9.0 compatibility

= 1.1.0 =
Rewritten code. Inserting map with more convinient manner by popup window

= 1.0.3 =
1 bug fixed

= 1.0.2 =
1 bug fixed

= 1.0.1 =
Plugin release. Operate all the basic functions.

== License ==

This plugin is copyright pluginus.net &copy; 2012-2017 with [GNU General Public License][] by realmag777.

This program is free software; you can redistribute it and/or modify it under the terms of the [GNU General Public License][] as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY. See the GNU General Public License for more details.

[GNU General Public License]: http://www.gnu.org/copyleft/gpl.html


== Upgrade Notice ==

