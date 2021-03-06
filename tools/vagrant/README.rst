==================
Vagrant Deployment
==================

Requirements
------------

* Hardware:

  * 16GB RAM
  * 32GB HDD Space

* Software

  * Vagrant >= 1.8.0
  * VirtualBox >= 5.1.0
  * Git

Deploy
------

Make sure you are in the directory containing the Vagrantfile before
running the following commands.

Create VM
---------

.. code:: bash

    vagrant up --provider virtualbox

Validate helm charts are successfully deployed
----------------------------------------------

.. code:: bash

    vagrant ssh
    helm list
