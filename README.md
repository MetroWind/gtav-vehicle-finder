# GTA V/Online Vehicle Finder

# Introduction

So, [Simeon](http://gta.wikia.com/wiki/Simeon_Car_Export_Requests) is
asking you to find one of his five cars, and you are poor and will do
anything for 10k...  What would you do?  Would you search for car
names on Google one by one, and put them in 5 browser tabs?

But that’s lame!  You don’t want to constantly switch browser tabs!
It’s time to use this vehicle finder!

# Usage

Download the
[HTML file](https://github.com/MetroWind/gtav-vehicle-finder/raw/master/gtav-vehicle-finder.html)
to you machine, and open it in your browser.  Type in some keywords.

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

# Copying

Copyright © 2016 [MetroWind](https://github.com/MetroWind) <chris.corsair@gmail.com>

This work is free. You can redistribute it and/or modify it under the
terms of the
![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-2.png)
Do What The Fuck You Want To Public
License, Version 2, as published by Sam Hocevar.

               DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                       Version 2, December 2004
   
    Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>
   
    Everyone is permitted to copy and distribute verbatim or modified
    copies of this license document, and changing it is allowed as long
    as the name is changed.
   
               DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
      TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION
   
     0. You just DO WHAT THE FUCK YOU WANT TO.
