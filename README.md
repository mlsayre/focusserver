FocusServer
===========

Description: Simple local server built to show index.html page. Ideally should show all page content in a small, "focused" area in the middle of the page like so:

![](https://raw.github.com/mlsayre/focusserver/master/focusserver.png)

...but the CSS seems to be blocking the loading of the actual page. And, in fact, not all of the CSS is making it to the browser, either (when looking at page source in the browser). When only one CSS element is changed in the server file (like just background-color), about 3/4 of the index.html loads.

Also, the white background color area in the middle will only be shown if index.html happens to have an element with class "focus". A better approach would be to show a background image and padding. Will change when time allows.

The interesting (bad) code which needs to be fixed when I have the time:

                        

IO.copy_stream seems to be fickle.
