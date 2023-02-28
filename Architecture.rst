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
     - adc01.meeksnet.ca
     - adc02.meeksnet.ca
     - cm01.bigiq8.meeksnet.ca
     - dcd01.bigiq8.meeksnet.ca
  - vlan249:
     - layer2 to the servers 
     - layer3 default route

LabEnv2:
  - vlan250:
     - adc01-dr.meeksnet.ca
     - adc02-dr.meeksnet.ca
  - vlan251:
     - layer2 to the servers
     - layer3 default route

Production
  - vlan255





self document, itself, to create itself
nginx+docker+readthedocs+f5xc




sphinx 5.3.0 has requirement importlib-metadata>=4.8; python_version < "3.10", but you'll have importlib-metadata 3.7.3 which is incompatible.
sphinx-js 3.0.1 has requirement Jinja2<3.0,>2.0, but you'll have jinja2 3.0.3 which is incompatible.