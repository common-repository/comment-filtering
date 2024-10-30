=== Comment Filtering ===
Contributors: tempranova
Donate link: http://tempranova.com/comment-filtering/
Tags: comments, search, filter, datepicker, ajax, bootstrap
Requires at least: 3.0.1
Tested up to: 4.4.2
Stable tag: 4.4.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin creates a Bootstrap interface that allows users to search within your comments by a search term, a date range, or the recent past.

== Description ==

This plugin requires Bootstrap, and makes use of the Bootstrap Datepicker at https://eternicode.github.io/bootstrap-datepicker/.

This plugin creates a search area above comments on any post or page. Here, users can choose to enter a search term, enter a date range, or select an option of the recent past (Today, This Week, This Month) from a dropdown. They can also combine these options to search for terms within a certain time period. Please note, a selected "recent past" option will override a date range entered by the user.

The search uses AJAX to query your database for matching comments, and returns all of the relevant results in the comment area.

A term search searches both author names and comment content.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Use the Settings->Comment Filtering screen to configure your pagination.

== Frequently Asked Questions ==

= It doesn't look right, and it's not working? = 

Do you have Bootstrap installed and loading correctly? If not, head to https://getbootstrap.com/.

= Can I search only by date range? = 

Yes, you can search by any combination of search term and date range.

= Why isn't my custom date range isn't returning the right results? = 

Most likely, you have an option selected from the options for the recent past (Today, This Week, This Month). These will automatically override the custom date range you entered in.

== Screenshots ==

1. This shows what the search and filter interface looks like (Please note, Bootstrap is required)

== Changelog ==

= 1.0 =
* First release

== Upgrade Notice ==

= 1.0 =
* First release