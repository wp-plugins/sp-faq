=== WP responsive faq plugin ===
Contributors: SP Technolab
Tags: faq, faq list, faq plugin, faqs, faq with accordion, accordion, custom post type with accordion, frequently asked questions, wordpress, wordpress faq, WordPress Plugin
Requires at least: 3.1
Tested up to: 3.7
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A quick, easy way to add an responsive FAQs page.

== Description ==

This faqs plugin add a FAQs page in your wordpress website.

The plugin adds a "FAQ" tab to your admin menu, which allows you to enter Faq Title and Description items just as you would regular posts.

we have also used accordion function so that user can show/hide FAQ titles.

To use this plugin just create a new page and add this short code <code>[sp_faq limit="-1"]'</code>

= Features include: =
* Just create a FAQs page and add short code <code>[sp_faq limit="-1"]'</code>
* Easy to configure
* Smooth Accordion effect
* Smoothly integrates into any theme
* CSS and JS file for custmization

== Installation ==

1. Upload the 'sp-faq' folder to the '/wp-content/plugins/' directory.
2. Activate the sp-faq list plugin through the 'Plugins' menu in WordPress.
3. Add a new page and add this short code <code>[sp_faq limit="-1"]'</code>


== Frequently Asked Questions ==

= What festivals list FAQs are available? =

There is one templates named 'faq.php' which work like same as defult POST TYPE in wordpress.

= What's the easiest way to create my own custom version of the FAQs templates? =

For custom version you should have basic knowlage of wordpress ie "Register post type"
Just open "faq.php" file and change the labels name under FUNCTION sp_faq_setup_post_types { ... }

You can also change the css as per your layout

= Are there shortcodes for FAQs items? =

Yes, Add a new page and add this short code <code>[sp_faq limit="-1"]'</code>



== Screenshots ==

1. all Faqs
2. Add new Faq
3. preview

== Changelog ==

= 2.0 =
* Adds custom post type
* Adds FAQs
* New css and css file
* Smooth accordion effect

= 1.0 =
* Initial release
* Adds custom post type
* Adds FAQs


== Upgrade Notice ==

= 2.0 =
added new css and js file

= 1.0 =
Initial release