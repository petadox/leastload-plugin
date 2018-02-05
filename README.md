leastload-plugin
====================

By default Jenkins tries to allocate a jobs to the last node is was executed on. This can result in nodes 
being left idle while other nodes are overloaded. This plugin overrides the default behaviour and assigns jobs
to nodes with the least load. The least load is defined as a node that is idle or the one with the most available 
executors.

https://wiki.jenkins-ci.org/display/JENKINS/Least+Load+Plugin

[![Build Status](https://ci.jenkins.io/job/Plugins/job/leastload-plugin/job/master/badge/icon)](https://ci.jenkins.io/job/Plugins/job/leastload-plugin/job/master/)
