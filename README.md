OpenShift Sphinx Cartridge
==========================

An OpenShift cartridge to be used as an add-on for any primary cartridge.
This cartridge provides a [Sphinx Open Source Search Server](http://sphinxsearch.com/) installation.

Usage
-----

The cartridge can be added to any application either through the OpenShift web console or the [OpenShift client tools](https://developers.openshift.com/en/getting-started-client-tools.html)
using the URL http://cartreflect-claytondev.rhcloud.com/github/puzzle/openshift-sphinx-cartridge. 
Example using the OpenShift client tools:

    rhc -amyapp cartridge-add http://cartreflect-claytondev.rhcloud.com/github/puzzle/openshift-sphinx-cartridge
    rhc -amyapp app stop
    rhc -amyapp app start

Sprinx Version Info
---------------------
The [Sphinx](http://sphinxsearch.com/) version provided, currently *2.2.8*, is taken from the rpm provided by [Sphinx](http://sphinxsearch.com/) for RHEL/CentOS 6.

Sphinx sources are available at http://sphinxsearch.com/.
