#Paper Datepicker
*Date Picker based on Material Design and the design spec*

#install
bower init

bower install --save paper-datepicker

##How to Use
copy the file

bower_components/paper-datepicker/demo.html
to
index.html
...so you have a working file. 

Or just add the tag 
<paper-datepicker></paper-datepicker>
...where you want the date picker button to be

then add the link to the file
<link rel="import" href="bower_components/paper-datepicker/paper-datepicker.html">


While you’re working, you’ll need a basic HTTP server to serve your pages. If you have Python installed, you can run one of the following commands in the top level of the starter project.

###Python 2.x:

python -m SimpleHTTPServer

###Python 3.x:

python -m http.server

Test out the web server by loading the finished version of the project. For example:

http://localhost:8000

URLs in this tutorial assume your local server is listening on port 8000. If you’re using a different port, substitute the port you’re using.


This to be used as a Full Screen dialogue on a Desktop as well as Mobile

[google.com/design/spec/components/pickers.html](http://www.google.com/design/spec/components/pickers.html)

This is an extension of the Paper Input or Paper Button component with [Moment.js](https://github.com/moment/moment).
We have used for this example the Paper Button. All this using the Paper Full Screen Dialog experience of dominating a page so only one decision can be made.

We are trying to use the styling from the Polymer Demo calculator for the dates.

###Paper Button

[github.com/Polymer/paper-input](https://github.com/Polymer/paper-button)

which follows these [Paper Button Material Design Principles](http://www.google.com/design/spec/components/buttons.html)

###Paper Full Screen Dialog

[github.com/Polymer/paper-dialog](https://github.com/Polymer/paper-dialog)

which follows these [Full Screen Dialog Material Design Principals](http://www.google.com/design/spec/components/dialogs.html#dialogs-full-screen-dialogs)

###Similiar element
[Paper Calendar](https://github.com/Wenqer/paper-calendar/) by [Wenqer](https://github.com/Wenqer)
