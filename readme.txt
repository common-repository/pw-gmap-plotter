=== Google Maps Plotting ===
Tags: Plot events plot photos, plot places, markers, Google Maps, google map, multiple locations, Forward Geocoding, Reverse Geocoding, Geocoding
Requires at least: 3.8
Tested up to: 4.4.2
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html
Contributors: rohanmehta19
Stable tag: 1.2

Plot multiple addresses on a Google Map, with a simple short code.
== Description ==

**Features**

1. Plot Multiple Locations on a Map,
2. Marker Clustering,
3. Ability to click each marker to get more details i.e. through a Marker popup,
4. Marker's info popup details is customizable through shortcode and CSS,
5. Easy to use as works with simple shortcodes,
6. Ability to set initial zoom level through shortcode

Note: Before using this plugin you need to get Google Maps API key through the google developer console.
Once you enter the API key on the settings screen of the plugin it simply works with shortcodes and your XML markers

**For more information** 

1. How to get an API key, 
2. How to generate XML file dynamically,
3. Shortcode variations etc 
visit: http://phpwpinfo.com/wordpress-google-maps-api-plugin/

To display google map, you need markers in XML format and a simple configurable shortcode
Below is a sample XML

<markers>
<marker name="Some Place" topic="Some Topic" address="1st Street, City, Country" lat="6.8722333" lng="79.8632416" date="14-Feb-16" contact="" presenter="Mary" type="event"/>
</markers>

**Sample Shortcode**

[PW_PLOT_GOOGLE_MAP 
xml_file_path="/xml/sample_markers.xml"  
zoom=2 
html="topic,Topic|presenter,Presenter|date,Date|contact,Telephone / Mobile" 
]



== Installation ==

1. Upload the plugin files Google Maps Plotting in the same way you'd install any other plugin.
2. Activate the plugin

== Screenshots ==

Visit: http://phpwpinfo.com/wordpress-google-maps-api-plugin/


== Documentation ==

Documentation is available on: http://phpwpinfo.com/wordpress-google-maps-api-plugin/

== Frequently Asked Questions ==

Visit: http://phpwpinfo.com/wordpress-google-maps-api-plugin/


== Changelog ==

1.1
Fix: Security, Min width and height of the map

== Upgrade Notice ==

