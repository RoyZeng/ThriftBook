The Programmer's Guide to Apache Thrift
=======================================

Source for the examples in: The Programmer's Guide to Apache Thrift

http://www.manning.com/abernethy/

The book is organized into three parts:

Part I - Apache Thrift Overview
-------------------------------

A high level introduction to Apache Thrift and its architecture. Examples from this part are hello worldish. This part also covers basic Apache Thrift setup and debugging.

Part II - Programming Apache Thrift
-----------------------------------

This part digs into each layer of the Apache Thrift framework, examining transports, protocols, types, servers and the Apache Thrift interface definition language in detail. Examples from these chapters use C++, Java and Python as the demonstration languages. C++ examples provide makefiles and Java examples provide Build.xml files for building with make/ant respectively. All build scripts depend on Apache Thrift v1.0 (or the dev trunk). The Ant builds depend on SLF4J. The python examples are directly executable.

Part III - Apache Thrift Language Libraries
-------------------------------------------

This part of the book provides jump starts for the most popular platforms and languages used with Apache Thrift. The Web, and backend systems are examined through the lens of C++, Java, C#, JavaScript, Python, PHP, Perl and Ruby. The general idea is to add jump starts for every Apache Thrift language over time, though only the above mentioned languages will be in the printed book. Additional languages will be provided in online chapters (the Haxe jumpstart is already complete with source available in this repo). Part III also includes the final chapter, "Apache Thrift in the Enterprise", which takes a pragmatic look at the key advantages of Apache Thrift and some of the common best practices for developing with the framework.

Tools - Miscellaneous Thrift Stuff
----------------------------------

This folder is for various Thrift related stuff. Presently only a GEdit language file for Apache Thrift IDL.

Development Environment
-----------------------

The Dockerfile in the root of this repo defines a development environment for the book which will make it easy to build and test all of the examples in the book. This file only supports C++, Java and Python presently. Apache Thrift is undergoing two important changes on the way to v1.0. 

 - Support for C++11
 - Building the platform (compiler and all libs) with cmake

As things migrate I will update this Dockerfile. You can "$ docker run -it randyabernethy/thrift-book" to run the prebuilt image on Docker Hub (https://hub.docker.com/r/randyabernethy/thrift-book/).

[![](https://images.microbadger.com/badges/image/randyabernethy/thrift-book.svg)](https://microbadger.com/images/randyabernethy/thrift-book "Thrift Book Layers")

