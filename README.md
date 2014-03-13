Kotlin-X
========

Kotlin-X is a set of libraries written in [Kotlin](http://kotlinlang.org) that represent functionality that is cross-cutting against many vertical domains. That is, functionality that can be used independently of the business domain. Functinality such as HTTP, Logging, JSON, et al. many times aligned with infrastructura concerns. 

Why Kotlin-X?
=============

Kotlin is 100% Compatible with the JVM, which means you can use any existing Java Library in Kotlin applications and vica-versa, i.e. Kotlin libraries can be consumed by Java. The reason for Kotlin-X is that Kotlin provides a more succint and concise language allowing for more fluid and describable API's that can be used with little ceremoy. Kotlin-X is an aim to provide some of these functionalities. In fact, often Kotlin-X libraries might be nothing more than simple wrappers over existing JVM ones. 

What classifies as a Kotlin-X library?
======================================

A series of guidelines are used to define what constitutes a good candidate to be hosted under the Kotlin-X project

A Library should: 

* Should be OSS
* Should provide value over existing libraries available on the JVM. This can be both in terms of functionality and API simplicity (taking advantage of Koltin's language features).
* Should be cross-cutting concern.
* Should be well documented and have automated testss (unit or integration)
* Should not be bound to any business domain. 
* Should have a continuous integration project in place
 

What is this project?
=====================

This project is a placeholder for the README you're currently reading. It does not contain any source code. It is the organizational structure for Kotlin-X projects.

Current Libraries
=================

* [kotlinx.html](https://github.com/kotlinx/kotlinx.html) -- html building libirary
* [kotlinx.css](https://github.com/kotlinx/kotlinx.css) -- css building library

Potential Candidates
====================

* kotlinx.http
* kotlinx.logging
* kotlinx.json
* kotlinx.xml
* kotlinx.compression
* kotlinx.calendar
* kotlinx.drawing

