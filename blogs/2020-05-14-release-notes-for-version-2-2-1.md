---
title: Release Notes for Version 2.2.1
url: https://jclouds.apache.org/releasenotes/2.2.1/
date: '2020-05-14'
author: ''
feed_url: https://jclouds.apache.org/releasenotes/atom.xml
---
Introduction Release Highlights Known Issues Credits Test Results Introduction Apache jclouds 2.2.1 is the first bugfix release after jclouds 2.2.0 and comes with several bugfixes and performance improvements.
You can read the official announcement here . To get started with jclouds, please see the jclouds installation guide . Release Highlights New features in Apache jclouds 2.2.1 include: The jclouds Karaf integration and the jclouds CLI are no longer part of the jclouds releases. The projects are now
maintained by the Apache Karaf team and they will be released by them. Bugs and patches [ JCLOUDS-1520 ] -         JClouds is not using the JDK's KeepAliveCache when UntrustedSSLContextSupplier is used [ JCLOUDS-1529 ] -         NullPointerException in org.jclouds.json.gson.internal.JsonReaderInternalAccess.INSTANCE [ JCLOUDS-1533 ] -         Using Azure SAS Token unable to upload the file specific folder in the container [ JCLOUDS-1538 ] -         Expires header value is incorrectly formatted in S3 upsert requests [ JCLOUDS-1543 ] -         list() results are not in order when using withDetails [ JCLOUDS-1544 ] -         Unable to build javadoc with JDK >= 8 Improvement [ JCLOUDS-1540 ] -         Update Snakeyaml [ JCLOUDS-1541 ] -         Add Middle East (Bahrain) region to the AWS EC2 and S3 providers list The complete list of fixed issues and improvements can be found here . Known Issues JCLOUDS-1520 - JClouds is not using the JDK’s KeepAliveCache when UntrustedSSLContextSupplier is used. Credits jclouds would like to thank everyone who contributed time and effort in order to make this release happen: Especial thanks to the Apache Karaf team for taking over the jclouds-karaf and jclouds-cli projects to
make sure they will have continuity. Apache jclouds PMC and community for verifying the release. Check out who has been busy on Open Hub . Test Results Please see the discussion and the vote threads for live test results for 2.2.1: RC1 vote and discussion threads.
