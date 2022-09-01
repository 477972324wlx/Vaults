# Docker Network Review

1. Bridge
2. host
3. macVlan
4. IPLayer

***

## Bridge
1. Every instance has its own virtual eth interface
2. Every bridge is connected to the Host eth interface
3. Different bridge can be viewed as different subnets

***Pros: 
ISOLATION : Can Divide different subnets**
***

## Host
1. Instance will replace host's ipaddress, ports, etc

***Pros:
CONVENIENT: No need to map ports, configure networks

***

### Mac Vlan
*Explanation: map instance's address to physic device's ports*
***TBD***

***

## IP Layer
*Explanation: use host as a switch/router*




