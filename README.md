# Python Client/Server

Version 1.0 : 31-Dec-2017

Example Python project that illustrates client server exchanges using AJAX with JSON data.

Client side code is written in TypeScript.

The client index.html page has 3 edit boxes that hold numbers to be sent to a 'calculate' function on
the server. There is a 'result' box, and a 'Calculate' button.

When the calculate button is pressed, the 3 values are collected into a JSON object and sent to the
server via AJAX. The server adds the 3 values together and returns the sum, which is displayed on
the web page.

Have added 'start.sh' script that will start the server and open a google chrome window that will
be resized when the application starts. Substitute chromium-browser for google-chrome-stable if
you're using chromium.

**BONUS FEATURE**

Added window resize to 'client/index.ts' so that if the browser is started as a new window in
application mode, the window will become smaller to fit the user interface. There will be no
tabs, bookmarks, etc.

Yes, it's then a Web App...

You can start Chrome or chromium or Chrome from the command line to do this:
```sh
google-chrome-stable --new-window --app=http://localhost:8080/index.html
    --OR--
chromium-browser --new-window --app=http://localhost:8080/index.html
```
