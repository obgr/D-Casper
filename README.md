D-CasperJS
===================


Debian 9 &amp; PhantomJS based CasperJS image for Docker.

----------


Why CasperJS & PhantomJS?

They are basically great tools for creating Automated web based test suites.
> **[CasperJS](http://casperjs.org/ "The CasperJS Project's official Website"):**
> 
> CasperJS allows you to build full navigation scenarios using high-level functions and a straight forward interface to accomplish all sizes of tasks.

> **[PhantomJS](http://phantomjs.org/ "The PhantomJS Project's official Website"):**
> 
> PhantomJS is a headless WebKit scriptable with a JavaScript API. It has fast and native support for various web standards: DOM handling, CSS selector, JSON, Canvas, and SVG.


----------


Docker - Usage
-------------------

#### Run PhantomJS file in container
Example: Run hello.js from your working directory in a container.
```sh
docker run --rm -v $(pwd)/hello.js:/hello.js obgr/d-casperjs phantomjs hello.js
```
-------------

#### Run CasperJS file in container
Example: Run casper-test.js from your working directory in a container.
```sh
docker run --rm -v $(pwd)/casper-test.js:/casper-test.js obgr/d-casperjs casperjs casper-test.js
```
-------------

#### Run Image interactively
```sh
docker run -it obgr/d-casperjs:latest
```
-------------

#### Pull Image
```sh
docker pull obgr/d-casperjs:latest
```
-------------

#### Base your image on 
Start off your Dockerfile with: 
```sh
FROM obgr/d-casperjs:latest
```
-------------
