## CCNA by Shesh Chauhan IT Trainer
--------------------------------
* CISCO Exam v1.0(200-301)

* Exam D3scription :-

## Syllabus :- 

- 1.0 - Network Fundamentals                --> 20 %

- Network Access                            --> 20 %

- IP Connectivity                           --> 25 %

- IP Services                               --> 10 %

- Sequrity Fundamentals                     --> 15 %

- Automation and Programmability            --> 10%

# Introduction :-

### 1.  Network - 

- Network is a collection of multiple networking devices which are connected to each other 

### 2.  Networking -

- Start Communication between each other via network devices

### 3.  Interworking - 

- internetworking is a process in which user can start the inter communication using multiple network via networking devices .

## Types of Computer Network ?

* LAN   --> Small Area

* MAN   --> LAN + LAN

* CAN   --> campus

* WAN   --> geo

* PAN

## Transmission Mode and Transmission Media ?

### 1. Transmission mode :-

- It is a process to define the way of transmission . And there is two ways to transfer the data 

1. Simplex ( Device only send the data like keyboard mouse etc.)

2. Duplex ( there is two types of Duplex mode one is HDX and Other one is FDX )

- HDX support or send and receive the data but simultaneously in FDX both devices send the data simultaneously .

### 2. Transmission Media :-

1. Weired 

2. Wireless

* Wired transmission media - 3 types - coax and fiber and twisted

* Wireless media - RF , Blutooth , etc .



# Topology 
------------


## Topology

- Architecture of Network , Arrangement of networking devices . ( Physical and logical )

- BUS , STAR , MESH , RING , DUAL RING , HYBRID 


## Explain Topology :-

* HUB

* SWITCH 

* BRIDGE 

* REPEATER 

* MODEM 

* ROUTER 

* GATEWAY 

* ACCESS POINT 

* NIC CARD

## Bridge :-

* Bridge Connect two network segment to each other

## HUB :-

* single network segment convert multiple port .

* Broadcast

* traffic , collision 

* HDX

## Switch :-

* L2 & L3

* one segment into multiple segment

* Deliver the packet exact location

* ARP + RARP

* Single Network segment into multiple segment

* sequre 

* exact location

* ARP + RARP

* do not broadcast the information

* L2

* L3

* ARP = IP - MAC

* RARP = MAC - IP

* CAM = content address memory

* IP        |       MAc
            |
10.0.0.9    |       A
10.0.0.2    |       B

* AutoNegogiation - 

* onetime

## REPEATER :-

- LAN - 0-99

- Boost the Signal

## Modem :-

- Modems are used to transmit digital information via analog systems .

- The word  `modem` is derived from the term "modulator-demodulator."

- The essential functions of a modem are to modulate an analog carrier signal to carry digital information;

- and to demodulate a similar signal so as to decode the digital information from the analog carrier signal.



## Router :-

- Routers are multiport devices with high - speed backbones 

- Routers also support filtering and encapsulation like bridges .

- Like bridges routers are also self - learning , as they can communicate their existance . to other devices and can learn of the existance of new routers , nodes and LAN  segments .

- As explained earlier , they route traffic by considering the network as a whole . It shows than they use a high level of intelligence to accomplish this task .

- This characteristics makes than superior than hubs and bridges because they simply view the network on a link - by - link basis .

- The packet handled by router may include destination address , packet priority , level , least - cost route , minimum route delay , minimum route distance , and route congestion level .

- Routers constantly monitor the condition of the network , as a whole to dynamically adapt to changes in the condition of the network They typically provide some level of redundancy so that they are less susceptible to catastrophic failure .


## GATEWAY : 

- A Gateway is a piece of networking hardware used in telecommunications for telecommunications network that allows data to flow from one discreate network to another 

- Local Network <---> Gateway <---> InterNet
                        |
                        |
                    Router

## Access Point :-

- In Computer networking , a wireless access point , or more generally just access point , is a networking hardware device that allows other Wi-Fi devices to connect to a wiered network .

## NIC :-

- NIC allows both wired and wireless communications.

- NIC allows communications between computers connected via local area network (LAN) as well as communications over large - scale network through Internet Protocal (IP).

- NIC is both physical layer and a data link layer device , i.e it provides the necessary hardware circuitry so that the physical layer process and some data link layer processws can run on it .

## OSI Model :-

1. Application Layer :

* Create an interface between user and application

2. Presentation Layer :

* Create and manage Data Encode , Encrypt , Compress

3. Session Layer :

* Check target connectivity 

4. Transport Layer :

* Use TCP and UDP to transport the data 

5. Network Layer :

* Check best path for transmission 

6. Data Link Layer :

* Work on two sublayer 1 - LLC 2 - MAC

7. Physical Layer :

* Check physical connection


## TCP/IP Model :

```css
---------------------------------------------------------
TCP/IP Model     Protocals and services       OSI Model
---------------------------------------------------------
            |      HTTP , FTP           | Application
Application |      TELENT , NTP         | Presentation
            |      DHCP , PING          | Session
-------------------------------------------------------
            |                           |
Transport   |      TCP , UDP            |   Transport
            |                           |
-------------------------------------------------------
NETWORK     | IP,ARP,ICMP,IGMP          |   NETWORK
            |                           |
-------------------------------------------------------
NETWORK     |   Ethernet                |   Data Link
Interface   |                           |   Physical
-------------------------------------------------------
```


