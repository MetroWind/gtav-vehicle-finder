# GTA V/Online Vehicle Finder

# Introduction

So, [Simeon](http://gta.wikia.com/wiki/Simeon_Car_Export_Requests) is
asking you to find one of his five cars, and you are poor and will do
anything for 10k...  What would you do?  Would you search for car
names on Google one by one, and put them in 5 browser tabs?

But that’s lame!  You don’t want to constantly switch browser tabs!
It’s time to use this vehicle finder!

# Usage

Download the HTML file to you machine, and open it in your browser.
Type in some keywords.

# Technical stuff

When you open the page, you browser may be stuck for a little while,
because it’s downloading 370+ (small) images from the
[GTA Wiki](http://gta.wikia.com/wiki/Vehicles_in_GTA_V), and it may
use a bit more memory than usual.  But it shouldn’t be any problem for
a machine on which you can play GTA V.  After that things become
straight forward.  The program splits your search terms into pieces,
and use them to filter the cars.

The program is purely JavaScript written with
[React](https://facebook.github.io/react/).  Styling is done with
[Bootstrap](http://getbootstrap.com).

Sadly if you host this program on a sever, it won’t work.  Because
[Wikia](http://wikia.com/) doesn’t seem to support `XMLHttpRequest`
across domain.
