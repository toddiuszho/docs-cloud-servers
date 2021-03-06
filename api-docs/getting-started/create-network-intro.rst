.. _create-network-intro:

Create your first network
-------------------------

Rackspace first introduced networking services that were based on the OpenStack Nova-Network 
API and exposed these services via the ``/os-networksv2`` Cloud Servers extension.

These examples walk you through the steps to create an isolated network and create a server 
that is attached your isolated network. The simple exercises show you how to access the 
Networks extension API through nova client commands or cURL commands so that you can quickly 
create isolated networks and servers.

The exercises also help you learn how cURL commands and the Networks extension API work.

.. Note::

   This version of the network service is now superseded by the current networking API, 
   based on OpenStack Neutron, which offers a richer suite of networking services. To learn 
   more about neutron network operations, see 
   :rax-devdocs:`Cloud Networks Developer Guide <cloud-networks/v2/developer-guide>` 

- :ref:`Creating network<create-network>`
- :ref:`Listing networks<list-networks>`
- :ref:`Booting server with an isolated network<boot-server-with-net>`
- :ref:`Getting network details<get-network-details>`
- :ref:`Deleting network<delete-server>`

.. toctree::
   :maxdepth: 2

   Creating network <create-network/create-network>
   Listing flavors <create-network/list-networks>
   Booting a new server with your cloud network <create-network/boot-server-with-net>
   Getting network details <create-network/get-network-details>
   Deleting your cloud network <create-network/delete-network>