Permisson Bar
=============

Cookie Bar is a free & easy solution to the EU cookie law.

##### Why use Cookie Bar?

There is a lot of mystery and fuss surrounding the new EU cookie legislation, but it's essentially really simple. Cookies are files used to track site activity and most websites use them. Site owners need to make the use of cookies very obvious to visitors.

Cookie bar makes it simple and clear to visitors that cookies are in use and tells them how to adjust browser settings if they are concerned.

##### TL;DR

Just place this somewhere in your website and forget it:

    http://cdn.jsdelivr.net/cookie-bar/latest/cookiebar-latest.js

##### DEMO

Everyone wants to see a demo before downloading something, isn't it? You can see a demo here:

[http://cookie-bar.eu](http://cookie-bar.eu/)

##### How it works?

Permisson Bar is a drop-in and forget, pure vanilla javascript code, no jQuery or any other dependency needed. It shows up only when actually needed and stay silent if not: If a website has a cookie or some localStorage data set then the bar is shown, otherwhise nothing happens.

Once user clicks 'Allow Cookies' Cookie Bar will set a cookie for that domain with a name 'cookiebar' that will expire in 30 days. What this means is that the plugin will only show up once per domain (per month).

If a user decides to click "Disallow Cookies", Cookies Bar will simply remove all cookies and localStorage data (and will show up again the first time a cookie is detected).

##### How many languages are supported?

Currently, the supported languages for Cookie Bar are:

* it - Italian
* en - English
* fr - French

The user language is automatically detected by the browser, but you can force a specific language by passing an optional parameter (see below).

##### How to Install?

You have two options here:
<ol>
	<li>Use the hosted version (work in progress, you will see the link here ASAP)</li>
	<li>Or, 
		<ol>
			<li>Grab the Github repo and place it somewhere in a folder within your website. All of the files, including images and stylesheets, need to maintain it's relative structure - that is be in the same directory - for the plugin to work correctly.</li>
			<li>Put the code you have seen in TL;DR section somewhere on all relevant pages of your website.</li>
		</ol>
	</li>
</ol>

###### If you need to configure it, you can do it like that:

    http://cdn.jsdelivr.net/cookie-bar/latest/cookiebar-latest.js?forceYes=1&desiredParameters

##### Here is a short list of parameters you can use:

    forceYes=1 <= hides deny consent button and text
    forceLang=XX <= force a specific language
    blocking=1 <= blocks all the page until the user clicks deny or consent cookies
    
