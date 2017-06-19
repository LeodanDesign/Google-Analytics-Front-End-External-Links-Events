# Google-Analytics-Utilities
Adds Google Analytics Events To All Outgoing Links On A Web Page

Adds simple tracking of external links clicks to a webpage.

Available as a WordPress plugin.

Adds Javascript file (jQuery dependent) to wp_enqueue_scripts, loading the file in the code footer. Uses jQuery click function to attach to all <a> links, check if they are an external link by comparing the current domain to the link domain. If the link domain is different, it fires the ga('send', 'event') function available when analytics.js is loaded via the Google Analytics tracking tag / code.

Future Plans:
1.    Add ability to embed Google Analytics tracking code using property ID.
2.    Build a WordPress options page to allow adding of property ID.
3.    Embed Google Analytics tracking code in <head> tags of the webpage to allow Google Webmaster Tools & G-Suite domain management to use GA tracking code to identify site ownership.
4.    Allow implementation of Google Tag Manager as an alternative method of implementing Google Analytics tracking code with supporting documentation links.
5.    Use of Google Analytics API to pull in tracking ID.
6.    Use of Google Analytics API to pull in statistical data on posts, displaying information in a meta box / pop up in WordPress administration areas.
7.    Links to Google Analytics articles, documentation and tutorials.
8.    Add autoupdate from Github page feature.
9.    Submit to WordPress.org repository.
