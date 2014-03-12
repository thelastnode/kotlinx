Kotlin-X
========

Kotlinx is set of libraries that are are often needed in various applications, but not required for every project.

We defined the following rules for libraries here:

* Library shouldn't be bound to any business domain. Instead it should apply to specific technology domain.
* Library should have a high chance to cover most cases for particular domain, so that existence of a lot of different
  libraries for same topic is unlikely.
* Library should provide significant benefit to users for being written in Kotlin, by providing better APIs and
  integrating with language features.
* Library should be well documented and well tested.

This Project
============

This project doesn't contain source code, but is a place for common kotlinx documentation, list of libraries,
and handling meta-requests, like adding particular library under kotlinx umbrella, or requests to develop library
for the topic.

Repositories
============

* [kotlinx.html](https://github.com/kotlinx/kotlinx.html) -- html building libirary
* [kotlinx.css](https://github.com/kotlinx/kotlinx.css) -- css building library

Candidates
===========

* kotlinx.http
* kotlinx.logging
* kotlinx.json
* kotlinx.xml
* kotlinx.compression
* kotlinx.calendar
* kotlinx.drawing

