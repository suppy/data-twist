Data Twist
==========

An experimental script family to twist Open Data into new shapes.

Copyright (c) 2013 Shane Coughlan and Kana Fukuma

== Overview ==

These scripts are designed to take OpenStreetMap XML data and import it
into a geo-aware version of Wordpress. This allows information like shops
and tourist locations to quickly populate directories, at least in
theory.

The initial focus is on allowing OSM website XML downloads, XAPI pulls and
Osmosis node filters from a database to be converted into SQL files that we can
quickly load into a Wordpress install. There are some dependencies at the
moment, with the key item being the Geo Mashup plug-in for Wordpress to allow
us to store geo-references with each post.

Data Twist is not a solution for making local directories by itself. It is the
foundation for doing so via Open Data in the form of a OpenStreetMap's
database.

== Usage ==

To use the current root solution as of 19th February 2013, execute a command
with SCRIPT.rb <inputfile.name> <outputfile.name>

Then load the <outputfile.name> into your Wordpress MySQL database. Don't
forget to install Wordpress and it's Geo Mashup plug-in first.

== Warning ==

Current code is from a hack session and under rapid development.
Don't use with caution. Use with terror.

If this sets fire to your house, chases your cat up a tree, or causes you to
quit computers and become a vegetable farmer, don't blame us.

== License ==

Data Twist is Free Software. You can call it Open Source too. Whatever floats
your boat.

You can redistribute it and/or modify it under either the terms of the
2-clause BSDL (see the file BSDL), or the conditions listed in the LEGAL
file.

There is some sample data from OpenStreetMap included to test the scripts.
OpenStreetMap is open data, licensed under the Open Data Commons Open
Database License (ODbL). Find out more about this license here:
http://opendatacommons.org/licenses/odbl/