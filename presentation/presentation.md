Kantega REST workshop
==================================

<!--
Use Chrome for presentation

Time to complete this workshop should be around 3 hours.

It should be possible for everyone to complete this.

The design Assignment

-->

---

Setup

Make sure you have Java 7, Git and Maven 3.x installed

Try this from a command line:

  `mvn -version`

  `javac -version`

  `git --version`

---

To get started with the presentation navigate to the folder you keep your source code

and then write:

  `git clone https://github.com/olahast/RESTWorkshop`

---

Tip: To view this presentation locally, browse to install-dir/presentation and use
python or similar to setup a http server.

`python -m SimpleHTTPServer 8000`

---


Intro!
=====

1. What is REST and why do I need to learn about it
  * blabla  
2. Technology used for REST in java
3. Useful things used in this workshop
  * blabla
3. Workshop
4. Summary


---

Assignments
=====

Goal: Learn the basics of REST and a few advanced subjects

Learning the basics:

* A Basic REST service
* Using HTTP error codes
* Content type and serving up what the client wants
* Consuming REST via Angular
* Testing REST

Advanced stuff:

* Designing a REST Interface - different methodologies
* HATEOAS

---

### Topic 1. A basic Rest Service

A simple example of a Hello Rest application

    @Path("/hello")
    public class HelloWorldService {

      @GET
      @Path("/{param}")
      public Response getMsg(@PathParam("param") String msg) {

        String output = "Jersey say : " + msg;
        return Response.status(200).entity(output).build();
      }
    }

---

#### Assignment 1.1

There is a datamodel in /directory/ that should be exposed as a rest service

Create a get method that exposes it!

(Open localhost:8080/yourpath in a browser to see the results)

---

#### Assignment 1.1 solution

Solution here


---

#### Assignment 1.2

Create a full CRUDL interface for it.


#### Assignment 1.2 Solution

Solution here

---

### Topic 2. Error handling and HTTP Error codes

#### Assignment 2.1: Returning 404 not found when search fails.

Tips:

* Not happy with the way you solved Assignment #1?
* Try running `git checkout -f assignment-2` (WARNING: ANY LOCAL CHANGES WILL BE LOST)

The get operation should return 404 when the query turns up empty.

Make it so. (Hint: Error code is 404 - NOT_FOUND)

---

#### Assignment 2.1 solution

Solution here

---

#### Assignment 3

---

Congratulations, we are done!
----------------------------

What have we learned today?

---

Next steps?
-------------------

Reading:

Resources


---

Feedback and Q&A
=============

* Workshop:
  * Satisfied?
  * What to improve?
* Questions?
* Other feedback?
