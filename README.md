# WebMetal

A RESTful interface to hardware.

WebMetal falls somewhere in-between [RESTduino](https://github.com/jjg/restduino) and [JSFS](https://github.com/jjg/jsfs/).

Like RESTduino, WebMetal provides a [RESTful](https://en.wikipedia.org/wiki/Representational_state_transfer) interface to the hardware resources of the device it runs on (a technique pioneered by RESTduino).  This removes the need for device-specific IDEs, languages and electrical connections and instead allows the device to be controlled through [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) requests from a client-side web application or any other system capable of issuing HTTP requests.

Like JSFS, WebMetal provides a RESTful interface for storing and retrieving files, allowing client-side web applications to persist data.  In addition to storage, WebMetal expands on JSFS by adding an `executable` flag, allowing code stored in WebMetal's filesystem to be executed directly on the device running WebMetal.  These executable files can be triggered by a client application (via HTTP request), or by events internal to the WebMetal device such as a hardware interrupt, timer, etc.

WebMetal is written in [Python](https://www.python.org) and currently targets devices running [MicroPython](https://micropython.org).  A more general-purpose version targeting standard Python installations is on the roadmap, but resources are currently concentrated on delivering a functional, reliable release for MicroPython devices.

