Overview
========

LabEnv1 represents the production environment.  This environment is to be replicated 1 to 1 to LabEnv2

More indepth
------------

LabEnv1: 
  - vlan248:
    - DHCP for Management of devices
    - /32 static routes when required
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
