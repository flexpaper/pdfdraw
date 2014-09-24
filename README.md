pdfdraw
=======

A command line tool for drawing PDF to JPEG and PNG using node-webkit and pdf.js

Usage
-----
pdfdraw.exe [PDF file] [format] [Destination Directory] [Number Of Pages (optional)]

Building on Windows
-------------------
This is a node.js application which uses node-webkit to draw the pdf to jpeg or png. Packaging this application is done in the following manner:

1) Create a zip file of js, index.html, package.json > pdfdraw.zip<br/>
2) rename zip file to pdfdraw.nw<br/>
3) Merge by executing copy /b nw.exe+pdfdraw.nw pdfdraw.exe<br/>

License
-------------------
MIT License

<br/><br/>

<b>Maintained and sponsored by █▒▓▒░ <a href="http://flexpaper.devaldi.com/">The FlexPaper Project</a></b>
---------------
