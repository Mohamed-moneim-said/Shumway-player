# Shumway player
Shumway is a Flash VM and runtime written in JavaScript
## how to use Shumway player
First download clone project using this link "https://github.com/Mohamed-moneim-said/Shumway-player.git" and unarchive file

create a web page (e.g. demo.html) that includes shuobject.js:

    <script src='./bower_components/shumway-dist/shuobject.js'></script>
and, in a JavaScript, instantiate SWF file viewer similar to swfobject:

    shuobject.embedSWF('demo.swf', 'mainSWF', 800, 512, '9,0,10');
where mainSWF is a div element/container on the web page.

You shall have something like:

```<!DOCTYPE html>
<html>
<head lang="en">
  <meta charset="UTF-8">
  <title>Basic shuobject demo</title>
  <script src="./bower_components/shumway-dist/shuobject.js"></script>
  <script>
    // Create/embed SWF movie.
    shuobject.embedSWF('demo.swf', 'mainSWF', 800, 512, '9,0,10');
  </script>
</head>
<body>
  <h1>Demo</h1>

  <div id="mainSWF">Flash will be loaded here (it is similar to swfobject)</div>
</body>
</html>
```
Also add demo.swf file (e.g. from http://mozilla.github.io/shumway/demo.swf)

Viewing a SWF
Use a web server to view the created above page.
## Copyrights
This is a pre-built version of the Shumway source code.

See also https://github.com/mozilla/shumway

All rights saved to mozilla
