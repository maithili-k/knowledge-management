Grid Storage
*************


.. contents:: 
    :depth: 4


.. _storage-client:

===================================
Storage clients
===================================

.. _staging_files:

===================================
Staging files
===================================

.. _slow:
===================================
Slow speed/failures/stalling
===================================

1. A projectMine_ user located in the US has been having trouble accessing data on grid storage for months. He initially contacted us during the downtimes and DC move, but even in Novemeber and December we have been unable to fully resolve the problem: connection issues, slow speed, termination of data download mid-way, stalling of transfers, etc.

- A performance bottleneck was created after the move which was resolved. This improved the speed but not too much.

- Two broken network interfaces on our side which were stalling the data transfer. That was fixed, MTU numbers checked, problem persisted. 

- Various upgrades and tests but we do not have a solution yet. For now the user is getting access to the data via a VM on cloud.

_https://helpdesk.surfsara.nl/ticket/13812
