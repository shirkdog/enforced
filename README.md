enforced
==========

BSD Licensed Configuration Management tool

Copyright (C) 2015 Michael Shirk, Daemon Security Inc.

enforced aims to be the goto configuration management tool, utilizing the best features from the following
configuration management tools:

 * CFEngine
 * Puppet
 * Ansible
 * Salt

Every one of these tools provides a specific great feature. The idea behind enforced is to combine these features into a simple, unified tool for system management.

## Features and Capabilities (Planned)

 * Utilizing a similar promise theory to CFEngine (if the configuration is correct, good, otherwise report and reconfigure)
 * Powerful access to the remote systems similar to the Salt Master node reaching out to the Minion nodes (management that scales up to a large number of systems)
 * Fast, Scalable and built with security in mind (the goal would be to program this in C for speed, possibly with python extensions)
 * Option for Ansible style SSH management or single management port (yet to be determined)

## Note

This is currently just a idea, though some code will be following at some point. Current roadmap is the following:
 
 * Single box enforcement of configuration options
 * Flush out configuration protocol to be used
 * Test root node functionality with child nodes 
 * Build out additional capabilities as functions the root node can perform. 

