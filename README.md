## Intro

My Website.  Under Construction.

## Install

1.  Install [node.js][1]
2.  Install [bower][2]
3.  `npm install`
4.  `bower install`

## Build

1.  Test:  Uncompiled, unminified:
  `grunt test`
2.  Dist:  Compiled, minified:
  `grunt dist`
3.  Gzip:  Compiled, minified, gzipped:
  `grunt gzip`

## Run

1. If you built Test: 
  `grunt connect:test`
  ([http://localhost:3001][3])
2. If you built Dist:
  `grunt connect:dist`
  ([http://localhost:3000][4])
3. If you built Gzip:
  `grunt connect:dist`
  ([http://localhost:3000][4])

You can leave the webserver running while you rerun the build tasks and it will 
auto-update.  Watch task in progress.

[1]:http://nodejs.org/
[2]:http://bower.io/
[3]:http://localhost:3001/
[4]:http://localhost:3000/
