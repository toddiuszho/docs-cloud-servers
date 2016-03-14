.. _attach-network-intro:

Attach your network to an existing server
------------------------------------------

Use the Cloud Networks virtual interface extension to:

-  Create a virtual interface to a specified network and attach the network to an existing 
   server instance.
-  List the virtual interfaces for a server instance.
-  Delete a virtual interface and detach it from a server instance.

You can create a maximum of one virtual interface per instance per network.

**IMPORTANT: Can I attach/detach a Cloud Network on a running RackConnected Cloud Server?**

From `RackConnect v2.0 with Cloud Networks FAQ
<https://support.rackspace.com/how-to/rackconnect-v20-with-cloud-networks-faq/>`_:

    Attaching/detaching a Cloud Network on a running RackConnected Cloud Server causes the network stack to be reset, which will break the cloud server’s RackConnect connectivity. Therefore, we do not recommend attaching or detaching Cloud Networks to running RackConnect servers. If you do need to attach or detach a network, please contact your Support team prior to making the change.

These examples walk you through the steps to create a virtual interface to a specified 
network and attach the network to an existing server instance. The simple exercises show 
you how to access the Cloud Networks virtual interface extension through nova client 
commands or cURL commands.

- :ref:`Creating a virtual interface<create-virt-interface>`
- :ref:`Listing virtual interfaces for a server<list-virt-interfaces>`
- :ref:`Deleting a virtual interface from a server <delete-virt-interface>`

.. toctree::
   :maxdepth: 2

   Creating a virtual interface <attach-network/create-virt-interface>
   Listing virtual interfaces for a server <attach-network/list-virt-interfaces>
   Deleting a virtual interface from a server <attach-network/delete-virt-interface>
