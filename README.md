# Galileo
A tiny speck in the sky of web tools: let users tell you just how much they love your website.  



## Concept
Galileo is a lightweight Wordpress plugin that will poll your website’s users with a simple, unobtrusive star survey.  Get a sense for how users feel about your site without elaborate backend configuration and dashboards (annoying for you), or obnoxious popups and 12-page surveys (annoying for them).

If your site polls high, great! You can move on to solve other problems.  If your site polls low, then a more comprehensive user survey / feedback tool may be your next step.



## Installation
Install it just as you would any other Wordpress Plugin. Add the plugin folder to your plugins directory.  



## Usage
Admin settings:
- Choose the pages on which the star survey should appear
- Specify a delay for its appearance
- Specify the corner in which it should appear
- Specify usage on mobile, tablet, or desktop

A simple script will be included near the bottom of the targeted pages, and a basic stylesheet will be added to the head. The plugin does require jQuery.

Admin stats:
- The list of votes received
- Your running average, total number of votes, and breakdown by device
- Export vote data as a CSV or JSON

Galileo will create its own table in your database to capture votes.  This will be removed if the plugin is deleted, so be sure to export your data before ever deleting it!



## Customization
The public elements can be customized with CSS.  Simply target the content with these selectors:_[inserts public selectors here]_

Your theme's stylesheet should be included after this plugin's base stylesheet.

If you would like to use your own styles entirely, deselect the "Output Default Styles" option in the plugin settings.



## License
_[TODO] Unsure how to license this plugin, actually.  Will need to do my homework on Wordpress licensing_

A copy of the license will be included in the root of the plugin’s directory as `LICENSE`.



### Support, Issues, Development
The plugin is provided as-is with no pretense of commercial support.

Feedback is welcome and encouraged.  Issues, suggestions, and development are managed through Github.



## Credits
This project is built on the shining north star of plugin frameworks, [Wordpress Plugin Boilerplate](http://wppb.io/), and includes the magical and transcendent [ACF by Elliot Condon](https://www.advancedcustomfields.com/).

All additional code, comments, and opinions expressed in this plugin are my own, or the contributions of the esteemed Github community.

Phil Ensminger
[ensm.in/ger](http://ensm.in/ger)

> NOTE: This plugin does not yet exist.  This README is the first test of its viability and potential usefulness.  Would you use a plugin like this?  Do you identify with the problem that it solves? How could it be better?  Tell me. phil@ensminger.io
