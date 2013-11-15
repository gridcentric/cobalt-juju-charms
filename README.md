README
======

Charms for deploying Gridcentric VMS and Cobalt extensions.

Usage
-----

These charms are configured to deploy on different Ubuntu versions, so they may
be added to any release branch.

To use them locally (with `precise`, for example), you can do the following.

    mkdir cobalt-juju-charms && cd cobalt-juju-charms
    git clone http://github.com/gridcentric/cobalt-juju-charms precise
    juju deploy --repository=. local:cobalt-compute
    juju deploy --repository=. local:cobalt-api
    juju deploy --repository=. local:cobalt-horizon

Then add the relations as specified in the individual charms.

    juju add-relation nova-compute cobalt-compute
    juju add-relation nova-cloud-controller cobalt-api
    juju add-relation openstack-dashboard cobalt-horizon
