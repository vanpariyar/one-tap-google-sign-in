=== One Tap Google Sign in ===
Contributors: surendhar153
Donate link: https://bit.ly/paypal-surendhar153
Tags: google, one tap, social login, login, signup, yolo, you only login once
Requires at least: 5.1
Tested up to: 5.5
Requires PHP: 7.0
Stable tag: 1.1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
 
Allows users to add Google One Tap Sign-in Or Sign-up to wordpress website.
 
== Description ==

Allows users to add Google One Tap Sign-in Or Sign-up to wordpress website.


== Installation ==

1. Install the plugin via Wordpress repository or by uploading the plugin
2. Activate the plugin through the 'Plugins' menu in WordPress
4. In the Google Cloud Console create a project and create a oauth app
5. And create credentials for "OAuth client ID" and choose web application and add your homepage to 'Authorized JavaScript origins' and you can leave 'Authorized redirect URIs' empty.
5. Get the 'Client ID' from your credentials
6. Enter your 'Client ID' of you oauth login credentials in the 'Google One Tap Login' menu in the wordpress

== Dependencies ==

1. Wordpress v5.1 and later
2. PHP v7.0 and later

== Frequently Asked Questions ==
 
= How does login works? =
 
When google sends user information, if the user email is already registered it will login the user and if the user email is not registered it will create a user account and it will login the user. And after logging in the user will be redirected to the same page.
 
= How to select user role of registering user? =

New user registration user role is defined in the 'New User Default Role' field in the Settings -> General in the admin menu.

= How to enable Automatic sign-in in one tap login? =

Automatic sign-in is currently not enabled. You can look for this feature in the upcoming release
 
== Changelog ==

= 1.1.2 =
* Updating User Firstname Lastname and getting profile picture for future use
* Added security fixes sanitize input and output

= 1.1 =
* Updating User Firstname Lastname and getting profile picture for future use
* Added security fixes sanitize input and output

= 1.0 =
* Added Lisence and added guidlines for wordpress plugin repository
 
= 0.0.1 =
* Google One Tap Sign-in added for wordpress
