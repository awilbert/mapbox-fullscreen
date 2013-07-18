#MapBox Fullscreen#

A simple way to implement a true fullscreen map viewing experience using HTML 5's canvas. Other "fullscreen" methods simply fill the browser window with the map. This one removes all browser chrome and literally fills the entire screen.

The trick is to wrap the map inside of two divs. The outer div will provide the positioning and size on the webpage. The inner div will scale up with requestFullScreen().

###View [the map][view].###


[view]: https://rawgithub.com/awilbert/mapbox-fullscreen/master/mapbox-fullscreen.html
---

###Additional Resources###
* [Mozilla Developer Resources][01]


[01]: https://developer.mozilla.org/en-US/docs/Web/Guide/DOM/Using_full_screen_mode?redirectlocale=en-US&redirectslug=DOM%2FUsing_fullscreen_mode
