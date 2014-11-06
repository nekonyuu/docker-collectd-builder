## Description
This docker allows to build collectd's RPMs in a contained environment. Built RPMs support CentOS 6 only for now.

# Building

You can either use the public image or build it yourself. The public one :

    docker run -v $(pwd):/target nekonyuu/collectd-builder

This will build the RPMs and copy them in your current folder. You just need to modify "$(pwd)" by your chosen path if you want them at another place.
