Feature: Offline Mode
=====================

Specification
~~~~~~~~~~~~~


For an app to have the Offline Mode feature, it must be able to operate even when a device it is running on has no internet connection.
 
The app must also display to the user the network state (online/offline) using a visual indicator.

.. note:: The app may have to handle events where a call to an outside service will be made, while offline. These events can be dealt with via a queue or similar implementation, but the implementation is not relevant to this feature specification. See `Message Queuing <message-queuing.rst>`_.

Sample rendering:

.. image:: ./images/online-offline-indicator.png
