---
title: jclouds 1.5.3 out the door
url: https://jclouds.apache.org/blog/2012/11/17/jclouds-1-5-3-out-the-door
date: '2012-11-17'
author: ''
feed_url: https://jclouds.apache.org/blog/atom.xml
---
Released on 2012-11-14, jclouds 1.5.3 includes minor fixes, and a few important updates. New openstack-cinder and rackspace-cloudblockstorage-us/uk providers Add new Asia Pacific (Sydney) Region [ap-southeast-2] New TagApi for ec2, in a revised syntax similar to openstack-nova Handle network failures in large container (1M+) deletes in blobstore jclouds-cli and jclouds-karaf now provide a more intuitive file-based interface for reading and writing blobs. Many thanks to the contributors in this release of jclouds , jclouds-chef , jclouds-karaf , and jclouds-cli . Also many thanks for the diligence of our review team: Andrew Gaul and Matt for code, and Becca on docs. Moreover, we’re indebted to BuildHive for checking over 500 pull requests to date! On a build side, we currently validate both JDK6 and JDK7 on each pull, thanks to Andrew Phillips . Please update to jcloud 1.5.3 and check the new features. Particularly, try things out using JDK7. If you have questions, ping our user group or tag your question with jclouds on stackoverflow . We are working on 1.6 now, which includes a lot of cleanup and mechanisms to make less api calls when starting groups of machines. If interested in helping us out, hop onto IRC freenode #jclouds or join our dev group.
