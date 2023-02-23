Architecture Overview
=====================

LabEnv1 represents the production environment.  This environment is to be replicated 1 to 1 to LabEnv2

Diagram
-------

.. image:: architecture.png
   :class: no-scaled-link
   :width: 100%

More indepth
------------

LabEnv1:
  - vlan248:
     - DHCP for Management of devices
        - adc01.meeksnet.ca
        - adc02.meeksnet.ca
        - cm01.bigiq8.meeksnet.ca
        - dcd01.bigiq8.meeksnet.ca
  - vlan249:
     - layer2 to the servers 
     - layer3 default route

LabEnv2:
  - vlan250:
     - DHCP for Management of devices
     - /32 static routes when required
  - vlan251:
     - layer2 to the servers
     - layer3 default route

Production
  - vlan255





self document, itself, to create itself
nginx+docker+readthedocs+f5xc
