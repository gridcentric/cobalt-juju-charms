README
======

This charm provides the API packages for [Cobalt](http://github.com/gridcentric/cobalt) from [Gridcentric](http://www.gridcentric.com).

Usage
-----

Simply deploy the charm and add a relation to nova-cloud-controller:

    juju deploy cobalt-api
    juju add-relation nova-cloud-controller cobalt-api

Contact Information
-------------------

Author: Adin Scannell <adin@gridcentric.com>
Report bugs at: http://www.gridcentric.com
