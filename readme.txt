=== Plugin Name ===
Contributors: levi.putna
Donate link: http://www.ozblog.com/
Tags: Terms, Use, agree, Privacy, Policy, welcome, MU, Open, Source
Requires at least: 2.0.2
Tested up to: 3.2.1
Stable tag: 2.0.0

This Plugin adds a Terms & Conditions agreement page the first time a user logs in and a welcome message for new members.

== Description ==

The WordPress Terms & Conditions plugin, pops up a Terms & Conditions agreement page the first time a user logs in. Instead of making the user agree to the Terms of Use when they join the site this plugin makes them agree to the terms and conditions the first time they login. In addition the new users are presented with a nice fully customisable welcome message after they agree to your Terms to help them get started using your blog.

For Wordpress installations setup with the multiple site option the Terms & Conditions will pop up the first time a user loges into there new site. 

Features
*	Works for both New Blogs and New users.
*	Customisable Open Source Terms of Use agreement.
*	Customisable Open Source Privacy Policy.
*	Customisable Welcome Message.
*	Can be integrated into a mature blog.
*	Support for both WordPress and WordPress MU.
*	No changes need to be made to the Sign up process.

== Installation ==

This section describes how to install the plugin and get it working.

Wordpress

1. Upload the plugin to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
4. If you want to use Wordpress to edit your terms of use, privacy policy and welcome message, chmod terms-of-use.txt to 0664 (make them writable). The install process will attempt to do this for you. 

NOTE: for additional security there is an .htaccess file included in the terms-of-use directory that douse not allow scripts to be executed from these files. This protects against code insertion.

5. You can now login and edit your terms of use, privacy policy and welcome message via Site Admin > Terms of Use.

Wordpress MU

1. Upload the plugin to the `/wp-content/mu-plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
4. If you want to use Wordpress to edit your terms of use, privacy policy and welcome message, chmod terms-of-use.txt to 0664 (make them writable). The install process will attempt to do this for you. 

NOTE: for additional security there is an .htaccess file included in the terms-of-use directory that douse not allow scripts to be executed from these files. This protects against code insertion.

5. You can now login and edit your terms of use, privacy policy and welcome message via Site Admin > Terms of Use.

== Screenshots ==

1. /tags/2.0.0/Screenshot1.png
2. /tags/2.0.0/Screenshot2.png

== Changelog ==

= 2.0 =
* Update to work with Wordpress 3.2.1

= 1.0.1 =
* Update install to try and make content files read write

= 1.0 =
* Update to work with Wordpress 2.5


== Upgrade Notice ==

= 2.0 =
Update to work with Wordpress 3.2.1