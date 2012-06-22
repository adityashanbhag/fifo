The fifo repository is a container for the project fifo components to keep track of versioning, it is ment to give one group of versions that are all compatible.

Components
==========
A quick list of components for details please look at the repos or http://project-fifo.net .

* erllibcloudapi - a library implementation the CloudAPI in erlang.
* libchunter - a library to communicate the chunter server.
* libsnarl - a library to communicate with the snarl server.
* libsniffle - a library to communicate with the sniffle server.
* snarl - a right management and option server.
* sniffle - central component of project fifo.
* wiggle - the web frontend.


Variabls
========
```
_OWN_IP_ - the nodes ip
_REDIS_URL_ - the url of the redis server
_REDIS_DOMAIN_ - the domain of the redis server
_FIFOCOOKIE_ - cookie for this fifo instance.
```

Reporting a bug
===============
if you report a bug please be so kind and provide the output from
```
./fifofy.sh collect
```
ran on the global zone, this will making it way easyer to track down the curlpit.
