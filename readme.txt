=== DamnSexyBookmarks ===
Contributors: Norman Yung
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=8HGMUBNDCZ88A
Tags: social bookmarking,bookmarks menu,digg,delicious,furl,myspace,twitter,facebook,technorati,reddit,yahoo 
Requires at least: 2.7
Tested up to: 2.7.1
Stable tag: 1.0.2

Adds a social bookmarking menu to your posts/pages/index.

Based on Josh Jones' SexyBookmarks plugin: http://eight7teen.com/sexy-bookmarks

== Description ==

= UPDATE v.1.0.2=
All additions made in DamnSexyBookmarks have been merged into to [SexyBookmarks](http://eight7teen.com/sexy-bookmarks). I'll continue working on changes there.

= 1.0 First Release =

Based on [Josh Jones' SexyBookmarks v.2.1.2 plugin](http://eight7teen.com/sexy-bookmarks).

It includes all the features of SexyBookmarks v.2.1.2 with the following changes/additions:

*	Customizable display order of bookmarks.
*	Uses WP Custom Fields to store the short URL for each post/page.
	This minimizes the need to make a remote request for a short URL each time the post or page is processed.
*	Fix to remove inline CSS when DamnSexyBookmarks is displayed in the feed.
*	Added an option to hide or display DamnSexyBookmarks in feeds.
*	Added an option to hide “Sharing is Caring” or “Sharing is Sexy”.
*	Streamlined code for easier maintenance.

________________________________________________________



== Credits ==

* Credit goes to [Josh Jones' SexyBookmarks plugin](http://eight7teen.com/sexy-bookmarks).

== Frequently Asked Questions ==

= Why is it named DamnSexyBookmarks? =

To pay homage to the plugin that this plugin is based on and got me into plugin development in the first place.

= I found a bug. How do I report it? =

You can contact me or leave a comment at the [DamnSexyBookmarks homepage](http://www.robotwithaheart.com/wordpress-work/damnsexybookmarks).

== Screenshots ==

1. Just an example...

== Installation ==

1. Upload the extracted archive to 'wp-content/plugins/'
2. Activate the plugin through the 'Plugins' menu
3. Open the plugin settings page Settings -> DamnSexyBookmarks
4. Adjust settings to your liking
4. Enjoy!

= Manual Usage =

If you would like to insert the menu manually, choose "Manually insert" from the options page, then place the following code into your theme files where you want the menu to appear:

`<?php if(function_exists('selfserv_sexy')) { selfserv_sexy(); } ?>`

You can still configure the other options available when inserting manually and they will be passed to the function. This is for those of you who have requested to be able to place the menu anywhere you choose... Enjoy!



== Changelog ==

*	**1.0** Initial release based on SexyBookmarks + additional changes:
	*	Customizable display order of bookmarks.
	*	Uses WP Custom Fields to store the short URL for each post/page.
	*	Fix to remove inline CSS when DamnSexyBookmarks is displayed in the feed.
	*	Added an option to hide or display DamnSexyBookmarks in feeds.
	*	Added an option to hide “Sharing is Caring” or “Sharing is Sexy”.
	*	Streamlined code for easier maintenance.
*	**1.0.1** Minor bugfix reported by XPH.
*	**1.0.2** Go to SexyBookmarks for latest updates. We're unifying development.