# Javascript-Voronoi
The implementation of Steven J. Fortune's algorithm to
efficiently compute Voronoi diagrams. 

## Core files
* rhill-voronoi-core.js

Where the Voronoi object is implemented. 

* rhill-voronoi-core.min.js

The minimized version

## Demo files

* rhill-voronoi-demo1.html
* rhill-voronoi-demo2.html
* rhill-voronoi-demo3.php
* rhill-voronoi-demo4.html
* rhill-voronoi-demo5.html

* mootools/*

Used by rhill-voronoi-demo3.php




## Main object: Voronoi

var voronoi = new Voronoi();
var bbox = {xl: 0, xr: 800, yt: 0, yb: 600}; // xl is x-left, xr is x-right, yt is y-top, and yb is y-bottom
var sites = [ {x: 200, y: 200}, {x: 50, y: 250}, {x: 400, y: 100} /* , ... */ ];

var diagram = voronoi.compute(sites, bbox);
```
