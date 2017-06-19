# Google-Analytics-Front-End-External-Links-Events
Adds Google Analytics Events To All Outgoing Links On A Web Page

Adds simple tracking of external links clicks to a webpage.

Available as a WordPress plugin.

Adds Javascript file (jQuery dependent) to wp_enqueue_scripts, loading the file in the code footer. Uses jQuery click function to attach to all <a> links, check if they are an external link by comparing the current domain to the link domain. If the link domain is different, it fires the ga('send', 'event') function available when analytics.js is loaded via the Google Analytics tracking tag / code.
