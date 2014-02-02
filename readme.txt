=== Debug Bar Query Count Alert ===
Contributors: mboynes, alleyinteractive
Tags: debug, developer, debug-bar, mysql, performance
Requires at least: 3.1
Tested up to: 3.8.1
Stable tag: 0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A simple add-on for the Debug Bar plugin to replace the button text with the database query count and time.

== Description ==

Replaces the default text in the Debug Bar button (which is "Debug Bar" by default in English) with the page's query count and total sql time. The button will be red if there were more than 200 queries or they took more than 1 second to run, and orange if the page required more than 100 queries or took more than 0.5 seconds to run.

Requires the [Debug Bar plugin](http://wordpress.org/plugins/debug-bar-console/) and for the constant `SAVEQUERIES` to be true.

Inspired by the Admin Bar on WordPress.com VIP, which offers similar functionality.

== Installation ==

1. Upload to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Can I alter the color-coded thresholds? =

Yes, absolutely. In your theme or plugin, you can set these values as follows:

`
# Lower the query count limits to 50 and 100
Debug_Bar_Query_Count_Button()->query_count_limits = array( 50, 100 );

# Lower the query time limits to 250ms and 500ms
Debug_Bar_Query_Count_Button()->query_time_limits = array( 0.25, 0.5 );
`

== Screenshots ==

1. This is the normal state.
2. This is the notice state.
3. This is the warning state.

== Changelog ==

= 0.1 =
Brand new.
