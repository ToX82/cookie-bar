cookieBAR
=============
[![](https://data.jsdelivr.com/v1/package/npm/cookie-bar/badge)](https://www.jsdelivr.com/package/npm/cookie-bar) [![Rate on Openbase](https://badges.openbase.com/js/rating/cookie-bar.svg)](https://openbase.com/js/cookie-bar?utm_source=embedded&utm_medium=badge&utm_campaign=rate-badge)

cookieBAR is a free & easy solution to the EU cookie law.

##### Why use cookieBAR?

There is a lot of mystery and fuss surrounding the new EU cookie legislation, but it's essentially really simple. Cookies are files used to track site activity and most websites use them. Site owners need to make the use of cookies very obvious to visitors.

Cookie bar makes it simple and clear to visitors that cookies are in use and tells them how to adjust browser settings if they are concerned.

##### TL;DR

Get to this page, configure the cookiebar to your needs and place the generated code somewhere in your web pages:

[https://cookie-bar.eu/#configuration](https://cookie-bar.eu/#configuration/)

##### How it works?

cookieBAR is a drop-in and forget, pure vanilla javascript plugin, with no jQuery nor any other dependency needed. It shows up when needed and stay silent when not: if a website has a cookie or some localStorage data set then the bar is shown, otherwhise nothing happens.

Once user clicks `Allow Cookies` cookieBAR will set a cookie for that domain with a name `cookiebar` that will expire in 30 days. What this means is that the plugin will only show up once month (this duration is configurable).

If a user decides to click `Disallow Cookies`, cookieBAR will simply remove all cookies and localStorage data (and will show up again the first time a cookie is detected).

Having a `cookiebar` cookie makes it simple to developers to check the user decision before activating external scripts (such as Google Analytics, or anything else). See [https://cookie-bar.eu](https://cookie-bar.eu/) for more informations.
