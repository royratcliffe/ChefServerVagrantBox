Vagrant Box Running an Opscode Chef Server with a Web UI
========================================================

You need to install [Vagrant](http://vagrantup.com/) and
[VirtualBox](https://www.virtualbox.org/). Run Bundler to install the necessary
gems. Then you can launch a local [Opscode](http://www.opscode.com/) Chef
server using

	vagrant up

It will take some time. As a one off, it downloads an Ubuntu 12.04.1 64-bit
server base box with Ruby 1.9.3-p194 compiled from source. On completion, you
will then find a local Chef server at [localhost:4000](http://localhost:4000)
and the web UI at [localhost:4040](http://localhost:4040).

Base Box
--------

The base box incorporates VirtualBox guest additions version 4.1.22 (at the
time of writing). You can easily rebuild the base box. See [instructions]().
