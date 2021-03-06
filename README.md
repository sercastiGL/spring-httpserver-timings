[![Build Status](https://travis-ci.org/sercasti/spring-httpserver-timings.svg?branch=master)](https://travis-ci.org/sercasti/spring-httpserver-timings)

# HTTP Server Timings library for Spring Boot projects

This library is based on the HTTP Server Timings spec, which you can find here: https://www.w3.org/TR/server-timing/. The main idea is to be able to determine if any slow downs, bottlenecks or unexpected application issues happened for a request just by looking at the Network Tab on the browser, without the need to look at console logs or installing any tools.

# Features
  - Generate response header with traces that will be rendered by the client browser to analyze response times
  - Use as annotation to trace a method, or inject the Tracing interface to trace a block of code

# Instructions
  - Add the dependency using maven/gradle
  - Use the @Traceable annotation or autowire/inject the Tracing interface

### TODO's
 - Create Sample app using library
 - Add kill switch from application properties
 - Chain Header from ServletRequest to support chaining (microservices)

License
----

MIT


**Free Software, Hell Yeah!**
