=== SOPA Blackout Plugin ===
Contributors: Chris Tidd, cgrymala, benwb
Donate link: http://www.sopawpblackout.com/
Tags: soap, blackout, pipa, censorship, sopa
Requires at least: 2.0.2
Tested up to: 3.3.1
Stable tag: 1.0.6

This plugin allows you to set SOPA blackout dates for your WordPress website. SEO friendly plus easy options to configure how often it's shown.

== Description ==

This plugin allows you to set SOPA blackout dates for your WordPress website, as well as a variety of options on who the anti-SOPA is shown too. You can have it shown instead of your site for any visitor, you can only show it the first time then let your visitors continue to the site, plus a lot more. This plugin is SEO friendly with temporary redirects being used.

By default, this plugin will automatically redirect visitors from your site's home page to a "Stop SOPA" message on Jan. 18 and 23, 2012. After the visitor has seen the Stop SOPA message, they will be able to continue to your site and will not see the message again during that browser session. There are a number of options available to customize the way the plugin behaves:

1. Blackout Dates - if you would like to change the dates on which the Stop SOPA message is displayed, you can enter a comma-separated list of dates (in YYYY-MM-DD format)
2. Remove backlinks to plugin sponsors - the default configuration of the Stop SOPA message displays a link to the 3 contributors/sponsors of this plugin. You can disable those by checking this box
3. Show the SOPA message to visitors the first time they visit your site, no matter which page they land on? - By default, only the front page and the posts page redirect visitors to the SOPA message. If you check this box, all pages will redirect the first time they visit your site.
4. Don't allow visitors to view the regular site when the SOPA message is active: - With the default configuration, this plugin sets a session cookie when a visitor sees the SOPA message, so that they won't see the message again until they close their browser. If you check this option, they will see the message every time they visit one of the affected pages, no matter how many times they've already seen it.
5. Link to the following page with the "Continue to site" link - If the "Continue to site" link is displayed on the SOPA page (in certain configurations, it won't be), you can choose which page on your site that link leads to (for instance, if you have the plugin configured not to set a cookie, then you should point visitors to a page other than your home page, since they won't see your site if they try to visit the home page).
6. Use the following page for the SOPA message: - By default, the plugin redirects to the actual PHP file that displays the SOPA message. You can choose to create a new page in WordPress to display the SOPA message, or choose to display the SOPA message in place of one of your existing pages.
7. Show an admin notice about this plugin - you can choose to show a message with links to more info about SOPA all the time (as long as this plugin is activated) or to show a nag message just when the SOPA message is actively being shown to visitors. The nag message will always include information about how the plugin is configured, so you'll be aware of when visitors should see the message. You can also choose to turn off the nag message altogether.
8. Make the "Continue to site" link lead to the visitor's original destination, instead of the page indicated above? - If you have the cookie enabled (default setting) so that visitors can continue through to your site after viewing the SOPA message, you can check this option to allow them to continue through to the page they originally tried to visit. Otherwise, they will be redirected to the page you chose in option #5 above (your home page by default).
9. Use the following page as a custom SOPA message instead of the one included in this plugin? - If you already have your own SOPA message set up within your site, you can choose it from the dropdown for this option, and the plugin will redirect to it instead of displaying the SOPA message that's included with this plugin.

When you deactivate this plugin, all of its settings will be removed. In addition, if you chose to create a new page, this plugin will automatically delete that page.

== Installation ==

To install the plugin:

1. Upload the files in the zip to the  to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Under Settings / SOPA Options you can configure the options for the plugin. 

== Frequently Asked Questions ==

Q. Are the redirects used SEO friendly?
A. Yes, 307 status headers are sent with the redirects, which are temporary and SEO friendly.

Q. Can I see an example of what the SOPA page looks like?
A. You bet! Take a look here for a demo http://www.wpsopaplugin.com/stop-sopa/

== Screenshots ==

1. To view a screenshot of the admin panel please see: http://www.sopawpblackout.com/wordpress-plugin-for-sopa-protest/

== Changelog ==

= 1.0.6 =

* New option: redirect to custom SOPA message
* New option: display admin notice about plugin
* New option: allow user to continue to original destination with "Continue to site" link
* Bugfix: Some options didn't save the first time you tried them
* Reorganized options screen
* Modified plugin to use WordPress time/date setting to determine current date, rather than server setting

= 1.0.5 =

* Reverts back to the codebase of 1.0.3, since 1.0.4 was accidentally released while it was still being developed.

= 1.0.3 =

* Added i18n to the Stop SOPA message page
* Removed logos from footer
* Removed Site5 link and replaced with link to BWB
* Added nofollow to footer sponsor links
* Added option to show nag message about this plugin

= 1.0.2 =

* Changed the link location for "Get the WordPress plugin" on the blackout page

== Upgrade Notice ==

= 1.0.6 =
New options available to redirect to original destination, display admin notice while active and to use your own SOPA message. Plugin also uses WordPress time settings to determine the current date, rather than using server time.

= 1.0.5 =
If you are running 1.0.3, no reason to update. If you updated to 1.0.4, this should fix the issue introduced by that version.

= 1.0.3 =
Removed logos from footer.

= 1.0 =
* Round 1 launch.
