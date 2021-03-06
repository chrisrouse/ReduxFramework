=== Redux Framework ===
Contributors: ghost1227, dovyp
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=N5AD7TSH8YA5U
Tags: admin, admin interface, options, theme options, plugin options, options framework, settings
Requires at least: 3.5.1
Tested up to: 3.7
Stable tag: 3.0.3
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Redux is a simple, truly extensible and fully responsive options framework for WordPress themes and plugins. Ships with an integrated demo.

== Description ==

Redux is a simple, truly extensible and fully responsive options framework for WordPress themes and plugins. Built on the WordPress Settings API, Redux supports a multitude of field types as well as custom error handling, custom field & validation types, and import/export functionality.

But what does Redux actually DO? We don't believe that theme and plugin
developers should have to reinvent the wheel every time they start work on a
project. Redux is designed to simplify the development cycle by providing a
streamlined, extensible framework for developers to build on. Through a
simple, well-documented config file, third-party developers can build out an
options panel limited only by their own imagination in a fraction of the time
it would take to build from the ground up!

= Online Demo =
Don't take our word for it, check out our online demo and try Redux without installing a thing!
[**http://demo.reduxframework.com/wp-admin/**](http://demo.reduxframework.com/wp-admin/)


= Docs & Support =
You can find [docs](http://reduxframework.com/docs/), [FAQs](http://reduxframework.com/docs/) and more detailed information about ReduxFramework on [reduxframework.com](http://reduxframework.com). If you were unable to find the answer to your question on the [FAQs](http://reduxframework.com/docs/), or in any of the [documentation](http://reduxframework.com/docs/), you should search [the issue tracker on Github](https://github.com/ReduxFramework/ReduxFramework/issues). If you can't locate any topics that pertain to your particular issue, [post a new issue](https://github.com/ReduxFramework/ReduxFramework/issues/new) for it.


= Redux Framework Needs Your Support =
It is hard to continue development and support for this free plugin without contributions from users like you. If you enjoy using Redux Framework, and find it useful, please consider [making a donation](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=N5AD7TSH8YA5U). Your donation will help encourage and support the plugin's continued development and better user support.

= Fields Types =

* Border
* Button Set
* Checkbox / Multi-Check
* Color (Wordpress Native)
* Gradient
* Date
* Dimensions (Height/Width)
* Editor (Wordpress Native)
* Gallery (Wordpress Native)
* Group (Repeatable/Non-Repeatable)
* Image Select (Patterns/Presets)
* Info (Header)
* Link Color
* Media (Wordpress Native)
* Multi-Text
* Password
* Radio (w/ Wordpress Data)
* Select (Select/Multi-Select w/ Select2 & Wordpress Data)
* Slider
* Sortable (Drag/Drop Checkbox/Input Fields)
* Sorter (Drag/Drop Manager - Works great for content blocks)
* Spacing (Margin/Padding/Absolute)
* Spinner
* Switch
* Text
* Textarea
* Typography 
 * The most advanced typography module complete with preview, Google fonts, and auto-css output!

= Additional Features =

* Field Validation
* Language Packs
* Full value escaping
* Required - Link visibility from parent fields. Set this to affect the visibility of the field on the parent's value.
* Output CSS Automatically - Redux generates CSS and the appropriate Google Fonts stylesheets for you on select fields. You need only specify the CSS selector to apply the CSS to (limited to certain fields).
* Oh, and did we mention a fully integrated Google Webfonts setup that will make you so happy you'll want to cry?


= Redux Framework is the solution for theme and plugin developers alike. =
At least we think so, we hope you feel the same.

  
= Translators & Non-English Speakers =
We need your help to translate Redux into your language. If you have created your own language pack, or have an update of an existing one, you can post [gettext PO and MO files](http://codex.wordpress.org/Translating_WordPress) to the [Github Repo](https://github.com/ReduxFramework/ReduxFramework) via a pull request or you can post an issue with the attached files. You can download the latest [POT file](http://plugins.svn.wordpress.org/redux-framework/trunk/ReduxCore/languages/redux-framework.pot), and see the latest [PO files in each language](http://plugins.svn.wordpress.org/redux-framework/trunk/ReduxCore/languages/).

= Current Translations =

Special thanks to the following people for language translations:

* German [de_DE] @Abu-Taymiyyah
* Bahasa Indonesia [id_ID] @riesurya

= Get Involved =
Redux is an ever-changing, living system. Want to stay up to date or
contribute? Subscribe to one of our mailing lists or join us on [Twitter](https://twitter.com/reduxframework) or [Github](https://github.com/ReduxFramework/ReduxFramework)!

NOTE: Redux is not intended to be used on its own. It requires a config file
provided by a third-party theme or plugin developer to actual do anything
cool!

== Installation ==

= Install the Plugin =
1. Upload the "redux-framework" directory to "~/wp-content/plugins/".
2. Activate the plugin through the "Plugins" area in WordPress admin panel.

= Activate "Demo Mode" =
On the Plugins page, beneith the description and an activated Redux Framework, you will find a Demo Mode link. Click that link to activate or deactivate the sample-config file Redux ships with.

= Start Building Your Own Panel =

1. Copy the "~/redux-framework/sample/" directory from within the plugin to a directory within your own theme or plugin.
2. Click on "Deactivate Demo Mode" in the "Plugins" area of the WordPress admin panel to turn off the Redux integrated demo.
3. Edit the "~/sample/sample-config.php" file (now copied to your plugin or theme directory) and change the $args['opt_name'] value to anything custom you would like. Make sure this is truly unque so other plugins/themes can use Redux.
4. Include the sample-config.php file: `require_once(dirname(__FILE__).'/sample/sample-config.php');` in your theme functions.php file or within your plugin's init file.
5. Modify the sample file to your heart's content.

= For Complete Documentation and Examples =
Visit: [http://reduxframework.com/docs/](http://reduxframework.com/docs/)


== Frequently Asked Questions ==

= Why doesn't this plugin do anything? =

Redux is an options framework... in other words, it's not designed to do anything on its own! You can however activate a demo mode to see how it works. 

= How can I learn more about Redux? =

Visit our website at [http://reduxframework.com/](http://reduxframework.com/)

= You don't have much content in this FAQ section =
That's because the real FAQ section is on our site! Please visit [http://reduxframework.com/docs/faqs/](http://reduxframework.com/docs/faqs/

== Screenshots ==

1. This is the demo mode of Redux Framework. Activate it and you will find a fully-functional admin panel that you can play with. On the Plugins page, beneath the description and an activated Redux Framework, you will find a Demo Mode link. Click that link to activate or deactivate the sample-config file Redux ships with.  Don't take our word for it, check out our online demo and try Redux without installing a thing! [**http://demo.reduxframework.com/wp-admin/**](http://demo.reduxframework.com/wp-admin/)

== Changelog ==

= 3.0.3 =
* Fixed Issue #129: Spacing field giving an undefined.
* Fixed Issue #131: Google Fonts stylesheet appending to body and also to the top of the header. Now properly placed both at the end of the head tag as to overload any theme stylesheets.
* Fixed issue #132 (See #134, thanks @andreilupu): Could not have multiple Wordpress Editors (wp_editor) as the same ID was shared. Also fixed various styles to match Wordpress for this field.
* Fixed Issue #133: Issue when custom admin stylesheet was used, a JS error resulted.


= 3.0.2 =
* Improvements to slides, various field fixes and improvements. Also fixed a few user submitted issues.

= 3.0.1 =
* Backing out a bit of submitted code that caused the input field to not properly break.

= 3.0.0 =
* Initial Wordpress.org plugin release.

== Upgrade Notice ==

= 3.0 =
Redux is now hosted on Wordpress.org! Update in order to get proper, stable updates.

== Attribution ==

Redux is was originally based off the following frameworks:

* [NHP](https://github.com/leemason/NHP-Theme-Options-Framework) 
* [SMOF](https://github.com/syamilmj/Options-Framework "Slightly Modified Options Framework")

It has now branched and been improved in many ways. If you like what you see, realize this is a labor of love. Please [donate to the Redux Framework](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=N5AD7TSH8YA5U) if you are able.
