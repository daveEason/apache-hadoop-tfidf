
-----------------------------------------------------

WELCOME
=======
This is a reasonably popular MapReduce application 'Term Frequency / Inverse Document Frequency' that illustrates how to use ToolRunner (see TermFreqInverseDocFreq.class) with Hadoop.

The application itself determines the 'relevance' of a particular sequence of phrases in an overall document, by
determining the frequency of the term grouping in contrast to the frequency of this grouping inversely throughout the entire set of documents being examined.

./pom.xml:
A maven project descriptor that describes how to build this module.

TESTING
=======

This  project also contains test classes that can be run as part of a test
suite.

BUILD
=====

> mvn package

ADDITIONAL RESOURCES
====================
Everything you need to know about getting started with the Cloudera CDH distribution
(including Apache Hadoop) can be found here: http://www.cloudera.com

Why Cloudera:
http://www.cloudera.com/content/cloudera/en/why-cloudera.html

Download CDH & Cloudera Manager:
https://ccp.cloudera.com/display/SUPPORT/Downloads

