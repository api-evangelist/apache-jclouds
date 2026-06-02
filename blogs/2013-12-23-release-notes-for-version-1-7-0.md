---
title: Release Notes for Version 1.7.0
url: https://jclouds.apache.org/releasenotes/1.7.0/
date: '2013-12-23'
author: ''
feed_url: https://jclouds.apache.org/releasenotes/atom.xml
---
Introduction jclouds version 1.7.0 is the first major release of jclouds as an Apache TLP, and the second release of jclouds as a TLP overall. You can read the official announcement at Apache jclouds 1.7.0 released . You can read the details of the specific JIRA issues addressed in this release at the JIRA Release Notes . To get jclouds, please see the jclouds installation guide . Notes jclouds 1.7.0 is incompatible with Guava 16. Please switch to
Guava 15.0 or earlier, or wait for jclouds 1.7.1 Reminder As per 1.6.1-incubating , the jclouds Maven group ID has changed from org.jclouds to org.apache.jclouds so a pom.xml dependency would now look like: <dependencies> <dependency> <groupId> org.apache.jclouds </groupId> <artifactId> jclouds-all </artifactId> <version> 1.7.0 </version> </dependency> </dependencies> Credits jclouds would like to thank everyone who contributed time and effort in order to make this release happen: Andrew Bayer for managing the release. Apache jclouds PMC for verifying. Check out who has been busy here . Test Results Please see the release discussion thread for test results for 1.7.0.
