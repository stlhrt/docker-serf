stlhrt:serf
=========================

Docker base container for main [_serf_](http://www.serfdom.io/) agent on Ubuntu Trusty Tahr in a serf cluster.

Exposes volume for _serf_ configuration files in /opt/serf/conf

No default configuration is provided in 50-defaults.json but can be overriden, just mount a directory with *.json files there and serf will load them.
