---
title: Release Notes for Version 2.5.0
url: https://jclouds.apache.org/releasenotes/2.5.0/
date: '2022-03-26'
author: ''
feed_url: https://jclouds.apache.org/releasenotes/atom.xml
---
Introduction Release Highlights Known Issues Credits Test Results Introduction Apache jclouds 2.5.0 is a regular release which includes compatibility and bug fixes.
You can read the official announcement here . To get started with jclouds, please see the jclouds installation guide . Release Highlights New features in Apache jclouds 2.5.0 include: Updated dependencies, particularly those that enable Java 17 support. Bugs and patches [ JCLOUDS-1588 ] -         Vulnerability detected in gson <2.8.9 [ JCLOUDS-1591 ] -         OAuth: ClientCredentialsJWTBearerTokenFlow.filter method throws Null Pointer Exception New Feature [ JCLOUDS-1596 ] -         Support Activity Log Alert Operations [ JCLOUDS-1597 ] -         Support Alerts operations Improvement [ JCLOUDS-1586 ] -         Upgrade to Guice 5.0.1 [ JCLOUDS-1589 ] -         Upgrade to Log4j 2.17.0 [ JCLOUDS-1590 ] -         Promote glacier to core [ JCLOUDS-1594 ] -         Allow overriding S3 with V4 signing [ JCLOUDS-1599 ] -         Add support for GLACIER_IR storage class The complete list of fixed issues and improvements can be found here . Known Issues This release does not include labs providers.  Users can depend on the SNAPSHOTs instead. Credits jclouds would like to thank everyone who contributed time and effort in order to make this release happen: Apache jclouds PMC and community for verifying the release. Check out who has been busy on Open Hub . Test Results Please see the discussion and the vote threads for live test results for 2.5.0: RC1 vote and discussion threads.
