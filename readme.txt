=== Super Simple Contact Form ===
Plugin URI: https://shinraholdings.com/plugins/super-simple-contact-form/
Contributors: bitacre
Donate link: https://shinraholdings.com/donate
Tags: contact, form, email, admin, shortcode, simple, small, tiny, send, mail
Requires at least: 2.8
Tested up to: 4.9.4
Stable tag: 1.6.2

An absurdly simple contact form plugin. Just type [contact]. There are no options.

== Description ==
This plugin creates the shortcode [contact] which will insert a small contact form. There are only name, email, subject, and message fields and the email will be sent to the administrator account's email address.

There are no options at all.

== Installation ==
1. Download the latest zip file and extract the `super-simple-contact-form` directory.
2. Upload this directory inside your `/wp-content/plugins/` directory.
3. Activate the 'Super Simple Contact Form' on the 'Plugins' menu in WordPress.
4. Type `[contact]` wherever you want a contact form.

== Frequently Asked Questions ==

= Is there a version with a reCaptcha? =
Yes! If you donate a couple bucks I'll send it to you. [Email me](mailto:plugins@shinraholdings.com).

= How do I set the options? =
You don't. There are no options. There's plenty of fancy, bloated contact form plugins out there you can use if you want options. This one works everytime with zero configuration.

= Where does the email go? =
To the administrator email address. You can change this in WordPress' general settings if you need to.

= Why did you make this? =
There were no good, up-to-date lightweight contact form plugins.

= Can you add this feature I just thought of? =
You can ask but I probably won't.

= How do I change the styling? =
You don't **need** to change the CSS styling, but you can if you want.

As of version 1.5.0, the plugin exclusively uses classes and IDs, no more inline styles. So you can change the CSS styles by adding rules for the relevant objects. The default style rules are as follows:

`.sscf-report {}
.sscf-wrapper {
	margin: 0;
	padding: 0;
	clear: both;
}
.sscf-input-wrapper {}
.sscf-input-wrapper label {
	width: 100px;
	float: left;
}
.sscf-input-wrapper input {
	width:280px;
}
.sscf-input-wrapper textarea {
	width:280px;
	height: 102px;
}
.sscf-submit {}
.clear {
	height: 0;
	visibility: hidden;
	clear: both;
	display: block;
	width: auto;
}`

There are additional classes and IDs for each item, should you require them, just take a look at the HTML source.


== Screenshots ==
1. The contact form.
2. The message when one of the requried fields (return email address or message) is omitted.

== Changelog ==
= 1.6.2 =
* Confirmed testing up to WP version 4.9.4.

= 1.6.1 =
* Purely cosmetic update for WordPress 4.4

= 1.6 =
* Moved CSS styles into their own stylesheet (sscf-style.css) instead of inline.
* Better object class organization and commenting.
* Added [Super Simple Contact Form] prefix back into the subject line.

= 1.5.4 =
* Fixes no message text

= 1.5.3 =
* Updated for 3.5.1 to use mail() instead of wp_mail(), which appears to no longer be working.

= 1.5.2 = 
* Now requires return email address and message. Will turn the fields red and print a message that "you forgot to include your email/message."

= 1.5.1 =
* Added info about reCaptcha (anti-spam) version

= 1.5.0 =
* Moved to an OOP framework.
* Removed inline styles in favor of full class/ID CSS styling.
* Fixed potential sanatization problems.
* Informational updates.

= 1.4 =
* Adds i18n framework for translations.

= 1.3.1 =
* Fixes bug where last letter of sender name was truncated. Again :)

= 1.3 =
* Removes hardcoded "send us a message" text.
* Coding and security updates.
* Adds i18n (multi-language support).
* Updated screenshot.

= 1.2 =
* Fixes bug where last letter of sender name was truncated.

= 1.1 =
* Fixes bugs related to echo/return.

= 1.0.3 =
* Fixed weird W3C validation error.

= 1.0.2 =
* First released version. 
* There may still be bugs, but I can't find any. 

== Upgrade Notice ==
= 1.6.2 =
Confirmed testing on WordPress 4.9.4.

= 1.6.1 =
Purely cosmetic update for WordPress 4.4.

= 1.6 =
Recommended upgrade, better code organization and WP standards compliance.

= 1.5.4 =
Critical upgrade.

= 1.5.3 =
Recommended upgrade, uses mail() instead of the broken wp_mail().

= 1.5.2 =
Recommended upgrade, now requires a return email address and a message to be sent.
 
= 1.5.1 =
Optional update, helpful for those curious about reCAPTCHA options or having problems with comment form spam.

= 1.5.0 =
Recommended upgrade, major overhaul.

= 1.4 =
Optional upgrade, helpful for non-English users.

= 1.3.1 =
Recommended upgrade, fixes the truncating of the last letter from senders name... Again... Sorry about that. :)

= 1.3 = 
Recommended upgrade, removes default "send us a message" text, adds i18n.

= 1.2 =
Recommended upgrade, old version will chop the last letter off senders name.

= 1.1 =
Recommeded update, older version may load too early on the page.
 
= 1.0.3 =
Not a critical update, but old version will not validate as W3C compliant.

= 1.0.2 =
Nothing to upgrade to, just a line to keep the validator happy.

== Readme Generator ==
* This plugin's readme.txt file was generated by the [bitacre Readme Generator](https://shinraholdings.com/tools/readme-gen) for WordPress Plugins.

== Support ==
* [Plugin Homepage](https://shinraholdings.com/wordpress/plugins/super-simple-contact-form/)
* [plugins@shinraholdings.com](mailto:plugins@shinraholdings.com)

== Donations ==
[Donations](https://shinraholdings.com/donate) are graciously accepted to support the continued development and maintenance of this and other plugins. We currently accept Paypal, link backs, and kind words. Also, checking the 'show plugin link' option on the widget helps us out greatly!
