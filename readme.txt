=== WP htaccess Optimize (beta) ===
Contributors: florianluce
Tags: htaccess, http, https, www, ssl, indexing, redirect, protect, caching, etags, compress, gzip, security, server
Requires at least: 3.7+
Tested up to: 5.0
Stable tag: 0.1.4
License: GPLv2 or later
Requires PHP: 5.6+
Text Domain: wp-htaccess-optimize
Donate link: https://www.paypal.me/florianluce

simply configure your htaccess to optimize your site!

== Description ==

With WP htaccess Optimize, you can easily optimize the performance of your site by configuring your htaccess in bit clicks

optimisation available:

* Time zone selection
* Prevents indexing of folders without index.php
* Disable the server signature
* Block Sensitive Files
* Protect WP-includes
* Protect author link
* Block author scans
* Enabling the tracking of symbolic links
* Comment spam
* Protection against file injections
* Various protections ( XSS, clickjacking and MIME-Type sniffing )
* Disable the hotlinking of your pictures
* Redirect without WWW
* Redirect http to HTTPS
* Caching files in the browser
* Disabled headers ETags
* Compress static files


== Installation ==

1. Unzip WP htaccess Optimize into your plugin folder
2. Go to WP htaccess Optimize settings, and select yours htaccess options
3. save it

== Changelog ==

= 0.1.4 =
* 30 march 2018
* Change TimeZone to UTC selector

= 0.1.3 =
* 27 november 2018
* Add 'Asia/Hô-Chi-Minh-Ville' time zone option

= 0.1.2 =
* 05 may 2018
* Adding cache control for ETags and prevent php errors

= 0.1.1 =
* 18 april 2018
* In time zone option, declare a default value to the variable out of the condition to prevent php errors
* Remove wrong setting in "Prevents indexing of folders without index.php", that crashes for old versions when activate

= 0.1.0 =
* 11 april 2018
* Launching
