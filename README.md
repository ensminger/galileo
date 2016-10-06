# Galileo
How does your website rate? Let's count the stars.



## Concept
Galileo is a lightweight Wordpress plugin that will poll your website’s users with a simple, unobtrusive star survey.  Get a sense for how users feel about your site without an elaborate backend configuration or dashboard (annoying for you), and no obnoxious popups or 12-page surveys (annoying for them).

If your site polls high, great! You can move on to solve other problems.  If your site polls low, then a more comprehensive user survey / feedback tool may be your next step.



## Installation
Install it just as you would any other Wordpress Plugin. Add the plugin folder to your plugins directory.  



## Usage
#### Settings
- Choose the pages on which the star survey should appear
- Choose a greeting and a thank you message (or add your own)
- Specify a delay for its appearance
- Specify the corner in which it should appear
- Specify usage on mobile, tablet, or desktop

A simple script will be included near the bottom of the targeted pages, and a basic stylesheet will be added to the head. The plugin does require jQuery.


#### Stats
- View list of votes received
- View your running average, total number of votes, and breakdown by device
- Export vote data as a CSV or JSON

Galileo will create its own table in your database to capture votes.  This will be removed if the plugin is deleted, so be sure to export your data first!



## Customization
The public elements can be customized with CSS.  Simply target the content with these selectors: `[TODO] inserts public selectors here`

Galileo's base stylesheet will be included near the top of the head array, so your theme / custom stylesheet should naturally override it.



## License
_[TODO] Unsure how to license this plugin, actually.  Will need to do my homework on Wordpress licensing._  A copy of the license will be included in the root of the plugin’s directory as `LICENSE`.



## Support, Issues, Development
The plugin is provided as-is with no pretense of commercial support.  Feedback is welcome and encouraged.  Issues, suggestions, and development [are managed through Github.](https://github.com/ensminger/galileo/issues)



## Credits
This project is built on the shining north star of plugin frameworks, [Wordpress Plugin Boilerplate](http://wppb.io/), and includes the magical and transcendent [ACF by Elliot Condon](https://www.advancedcustomfields.com/).

All additional code, comments, and opinions expressed in this plugin are either my own, or the contributions of the esteemed Github community.

-- Phil Ensminger | [ensm.in/ger](http://ensm.in/ger)

--------------

> NOTE: This plugin does not yet exist.  This README is the first test of its viability and potential usefulness.  Would you use a plugin like this?  Do you identify with the problem that it solves? How could it be better?  Tell me. phil@ensminger.io
