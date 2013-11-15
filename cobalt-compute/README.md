README
======

This charm provides the compute packages for [Cobalt](http://github.com/gridcentric/cobalt) from [Gridcentric](http://www.gridcentric.com).

Usage
-----

Simply deploy the charm and add a relation to nova-compute:

    juju deploy cobalt-compute
    juju add-relation nova-compute cobalt-compute

Contact Information
-------------------

Author: Adin Scannell <adin@gridcentric.com>
Report bugs at: http://www.gridcentric.com
