D-CasperJS
===================


Debian 9 &amp; PhantomJS based CasperJS "base image" for Docker.

----------


Why CasperJS & PhantomJS?
-------------
It is basically great tools for creating Automated web based test suites.
> **[CasperJS](http://casperjs.org/ "The CasperJS Project's official Website"):**
> 
> CasperJS allows you to build full navigation scenarios using high-level functions and a straight forward interface to accomplish all sizes of tasks.

> **[PhantomJS](http://phantomjs.org/ "The PhantomJS Project's official Website"):**
> 
> PhantomJS is a headless WebKit scriptable with a JavaScript API. It has fast and native support for various web standards: DOM handling, CSS selector, JSON, Canvas, and SVG.


----------


Docker - Usage
-------------------


####Run Image interactively
```sh
docker run -it obgr/d-casperjs:latest yourscript.cs
```

####Pull Image
```sh
docker pull obgr/d-casperjs:latest
```

####Base your image on 
Start off your Dockerfile with: 
```sh
FROM obgr/d-casperjs:latest
```
