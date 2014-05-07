RESTWorkshop
============

Rest workshop for Kantega

## Requirements ##

* Java 7 or 8
* Apache Maven 3.x
* Git
* Python (for simpleHTTPServer) or another http server for running the presentation locally
* Internet connection
* IDE (IntelliJ IDEA recommended)

## SETUP ##
### Download workshop project
1. git clone https://github.com/olahast/RESTWorkshop

## Assignments ##

1. My first REST service

The first task is to create a simple rest service

2. HTTP Error codes

The second task is to return different HTTP status codes for different results.

In a happy day scenario you would return HTTP 200 - OK, but if it is a search
and no results were found you can return HTTP 404 - Not found. A server error
would return a HTTP 500. etc.

3. Testing a rest api

4. JSON vs XML

5. consuming REST

6. Versjonering

7. HATEOAS service

A HATEOAS service has nothing to do with hating someone, it is a poorly named acronym
that stands for "Hypermedia as the Engine of Application State". There are a few java
frameworks for creating HATEOAS services and the most widely used is Spring-HATEOAS

http://projects.spring.io/spring-hateoas/
