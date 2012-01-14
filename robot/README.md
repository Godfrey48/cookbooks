Description
===========

Use this cookbook to setup the robotframework (http://code.google.com/p/robotframework/) and
to distribute your tests to the target systems.

The cookbook has yet only been tested on / implemented for Debian/Ubuntu.

Requirements
============

To use this cookbook, you need:

apt
java
python

The rest (robotframework etc.) will be installed through its recipes.

Attributes
==========

TODO: version

Usage
=====

You need a databag containing all test definitions and dependencies.

What you can do with it? You need to know about acceptance test automation and how they
are implemented/supported by the Robot Framework. When you know this, you will also know
that acceptance tests can be very slow. If you have a chance to run parts of your whole
suites on different machines in parallel, this cookbook will help you do so.
