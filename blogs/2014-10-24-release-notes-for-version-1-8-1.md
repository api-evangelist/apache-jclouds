---
title: Release Notes for Version 1.8.1
url: https://jclouds.apache.org/releasenotes/1.8.1/
date: '2014-10-24'
author: ''
feed_url: https://jclouds.apache.org/releasenotes/atom.xml
---
Introduction Highlights API Changes Known Issues Credits Test Results Introduction You can read the official announcement at Apache jclouds 1.8.1 released . You can read the details of the specific JIRA issues addressed in this release at the JIRA Release Notes . To get jclouds, please see the jclouds installation guide . Highlights Support for Google Cloud Storage Graduation of OpenStack Swift. The group ID changes from <dependency> <groupId> org.apache.jclouds.labs </groupId> <artifactId> openstack-swift </artifactId> <version> 1.8.0 </version> </dependency> to <dependency> <groupId> org.apache.jclouds.apis </groupId> <artifactId> openstack-swift </artifactId> <version> 1.8.1 </version> </dependency> API Changes openstack-swift API changes from 1.8.0 to 1.8.1 Known Issues Unfortunately openstack-neutron was broken in this release. If you depend on it, please skip this version. Credits jclouds would like to thank everyone who contributed time and effort in order to make this release happen: Apache jclouds PMC and community for verifying the release. Check out who has been busy on Open Hub . Test Results Please see the discussion thread and the vote thread for test results for 1.8.1. See this blog post for more information on POODLE and jclouds.
