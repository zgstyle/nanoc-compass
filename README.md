Nanoc + Compass bootstrap project
=================================

This directory contains a small nanoc project that uses Compass. Based on a site generated using `nanoc create_site`.

Places of interest:

* `src/config.rb` which contains the Compass configuration
* `src/sass` which contains the Sass stylesheets (and a partial)
* `Rules` which contains the rules for processing the Sass stylesheets

How To Use
----------

Before you do anything, make sure that you have Compass installed. Issue `gem install compass` if you haven't already or if you're unsure.

To compile the site, simply use `nanoc co`.

You may want to edit the Compass configuration (`src/config.rb`) to suit your needs.
