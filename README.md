enforced
==========

BSD Licensed Configuration Management tool

Copyright (C) 2015 Michael Shirk, Daemon Security Inc.

enforced aims to be the goto configuration management tool, utilizing the best features from the following
configuration management tools

 * CFEngine
 * Puppet
 * Ansible
 * Salt

Every one of these tools provides a specific great feature. The idea behind enforced is to bridge the gaps
into a simple, unified tool for enforcing configuration management. 

## Features and Capabilities (Planned)

 * Utilizing a similar promise theory to CFEngine (Keep the configuration, authorize report and reconfigure)
 * Powerful access to the remote systems similar to the Salt Master node reaching out to the Minion nodes (management that scaled up to a large number of systems)
 * Fast, Scalable and built with security in mind (the goal would be to program this in C for speed, possible with python extensions)
 * Option for Ansible style SSH management or single management port (yet to be determined)

