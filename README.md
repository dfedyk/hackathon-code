# hackathon-code
hackathon code for I2RS

This code depends on the following licenses: 
1) CONFD - from Cisco NET/DEV 
2) quagga - from http://www.nongnu.org/quagga/
3) yumacli-pro from YumaWorks 
4) ubuntu 14.04
5) virtual platform (mininet, etc) 
6) yang modules used

Changes to CONFD 
1) adding link from I2RS RIB to quagga new addition to quagga deamon to handle I2RS (i2rsd) 
   reads/writes and rpcs (add/delete rib, add/delete/modify route, add/delete nexthop) 
  [priority 1 - July 1 delivery] 
2) Add link for I2RS Filter-Based Topology model 
  [priority 2] 
3) Add link to/from topology yang modules to quagga deamon 
4) compiled yang modules (.fxs) plus database 
5) Build instructions

code related to yumacli 
1) all necessary yang files yumacli 
2) Any changes 
3) build instructions
