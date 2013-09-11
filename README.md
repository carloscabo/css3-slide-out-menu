css3-slide-out-menu
===================

(Almost) Pure CSS3 Slide Out Menu (In the Facebook fashion).

Based mainly in the Miguel Mota concept (with several modifications, read below).
<http://www.miguelmota.com/blog/slide-out-navigation-using-css3-translate/>

And other ideas / aproaches like:
<https://github.com/valdelama/responav>

And many other hints / tips by other people.

Features
========

- Lightweight (No iScroll.js)
- 3D Accelerated by OpenGL (Where avalibale)

Changes
=======

I think its better to have a minimun JS than use the "checkbox hack / trick", that gives some problems in Android browsers (and makes necessary to add some JS anyway...).

So I decided to change it by a traditional "toggleClass on the body element" approach, well know and very widespread tested. And that could be also achieved with a simple JS even without JQuery.

- Added JQuery 1.9.1
- Added Normalize.css

Bugs / Known Issues / Test
==========================

I've been testing it in iPhone 4 / 4S / iPad 2 / Android 4 and seems to work quite fine (with some small issues).

In Android 2 native browser the menu opens / closes but the scroll areas are inactive, I thing the only workaoround will be to add iScroll or another solution similar in the particular case.

TO-DO
=====

- Try to find a workaround in Android2 native browser.
