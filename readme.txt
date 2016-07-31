===BuddyPress Monster Widget===

Contributors: mercime, imath
Donate link: http://www.redcross.org/
Tags: buddypress, widget, theme development 
License: GPLv2 or later
Requires at least: WP 3.9, BuddyPress 2.1.1
Tested up to: WP 4.5.3, BuddyPress 2.6.1.1
Stable tag: trunk

Provides a quick and easy method of adding all BuddyPress core widgets to a sidebar for testing purposes.

==Description==

Based on Monster Widget, this plugin consolidates all BuddyPress core widgets into a single widget enabling theme developers to create multiple instances with ease. It has been created to save time during theme development and review by minimizing the steps needed to populate a sidebar with widgets. This widget is not designed for use in production.

BuddyPress widgets included:

* Log in 
* Members
* Who's Online
* Recently Active
* Friends
* Groups
* Sitewide Messages
* Recent Networkwide Posts

==Installation==

This plugin can be installed directly from your site.

1. Log in and navigate to Plugins &rarr; Add New.
2. Type "BuddyPress Monster Widget" into the Search input and click the "Search Widgets" button.
3. Locate the BuddyPress Monster Widget in the list of search results and click "Install Now".
4. Click the "Activate Plugin" link at the bottom of the install screen.
5. Navigate to Appearance &rarr; Widgets and [create a new instance](http://codex.wordpress.org/WordPress_Widgets#Activate_Widgets).

It can also be installed manually.

1. [Download](http://wordpress.org/extend/plugins/buddypress-monster-widget/) the plugin from WordPress.org.
2. Unzip the package and move to your plugins directory.
3. Log into WordPress and navigate to the "Plugins" screen.
4. Locate "BuddyPress Monster Widget" in the list and click the "Activate" link.
5. Navigate to Appearance &rarr; Widgets and [create a new instance](http://codex.wordpress.org/WordPress_Widgets#Activate_Widgets).

== Frequently Asked Questions ==

None at this time.

== Screenshots ==

1. From the admin dashboard: Go to Appearance > Widgets, click on the BuddyPress Monster Widget, select which sidebar you want to add it to, then click on the Add Widget button.
2. From the admin toolbar in the frontend: Click on your site title > Widgets, click on Widget Area, click on Add Widget button, select BuddyPress Monster Widget on the new panel, click on the Save and Publish button, and exit the Customizer.

==Changelog==

= 0.3 - June 15, 2015 =
* Fix Recent Networkwide Posts

= 0.2 - October 21, 2014 =
* Correct hook bp_widgets_init. Props @sbrajesh.

= 0.1 - October 13, 2014 =
* Original Release.

==Upgrade Notice==

= 0.3 - June 15, 2015 =
* Fix Recent Networkwide Posts.

= 0.2 - October 21, 2014 =
* Correct hook bp_widgets_init.