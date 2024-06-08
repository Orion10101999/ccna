# 2. Network 

- A fully interconnected group of devices is called network 

- Networking is more than just connecting cables 

- Modern networks carry different types of traffic having different requirements

    * Voice
    * Video
    * Text Graphics

- What is Internet ?

- What is Intranet ?

## 3. Internet - A Network of Networks 

- Internet is a network of Networks


## 4. What is Intranet ?

- Internal network of a company is sometimes reffered to as interanet.

## 5. What is networking ?

- Whatis.com

"In IT , networking is the construction , design , and use of network , including the physical (cabling , hub , bridge , switch , router , and so forth ) , the selection and use of telecommunication protocol and computer software for using and managing the network , and the establishment of operation polices and procedures related to the network . "

## 6. Devices on a Network Introduction ?

1. Desktop Computer
2. LAN Switch
3. Laptop
4. Firewall
5. Server
6. Router
7. IP Phone
8. Wireless Router
9. LAN Media
10. Cloud
11. Wireless Media
12. WAN Media

## 7. Expectations from Network

* Fault Tolerance

- Networks should limit the impact of hardware or software failure and should recover quickely when failure occurS.

* Scalability

- Network should be able to expand quickly to support new users and applications without impacting service to existing users

## 8. Components of Communication 

Message     Signal              Signal      Message

MessageSource-->Encoder-->Transmitter-->TransmissionMedium"TheChannel"-->Reciever-->Decoder-->MessgeDestination

## 9. Network Types 

Network Types           Stand For

LAN                 Local Area Network
WAN                 Wide Area Network
CAN                 Campus Area Network
MAN                 Metropolitan Area Network
SOHO                Small Office Home Office


## 10. Local Area Network 

- A network which is designed for small geographical area is called LAN

- for Example :-

- a department od an organization

## 11. Wide Area Network 

- A network which provides transmission of data between geographically distant locations is called Wide Area Network.

- Example - Internet

## 12. Campus Area Network 

- A network which is designed to provide connectivity to users or employees in campus .

- It is a bigger version of LAN .

- for Example - A campus of a colege or university

## 13. Metropolitan Area Network 

- A network which covers entire city using LAN technology is called MAN . It is like a bigger version of LAN

- A local ISP networks is a godd example of Metropolitan Area network .

## 14. SOCHO

- Small Office/Home Office- Network in small enterprises and home where the number of users is less .


## 15. Data Center

- A Data Center is facility used to house computer systems and associated components .

- It generally includes redudant or backup power supplies , redundant data , communication connections , and various security devices .

- Enterprise Data Center Infrastructure 

## 16. Communication needs Rules 

- Rules for any communication - Protocol

- Human communication components :

    * Sender and reciever 

    * Method of communicating

    * Common language and grammar

    * Speed and timing 

    * Confirmation requirements

## 17. Protocol - Propriety and Standard

* Earlier more propriety

* IEEE Standard - 802.11 - WiFi

* IETF Standard - IP , TCP , HTTP , FTP

* IETF keeps standard protocal in form of RFCs ( Request For  Comments)

## 18. Multiple Protocals and Layers 

                | DATA  |
           | L4 | DATA  |
      | L3 | L4 | DATA  |
 | L2 | L3 | L4 | DATA  |


                                  | HTTP Header | Data |

                     | TCP Header |      Data          |

         | IP Header |                   Data          |

---------------------------------------------------------

| Frame Header |     Frame Data         | Frame Trailer |

---------------------------------------------------------

| Frame Header |  IP Header  | TCP Header | App Header | I MEDITA | Frame Trailer |

---------------------------------------------------------

## 19. Encapsulation and Decapsulation Concept 

- A process of adding extra information around data on a particular layer in the form of header and trailer is called Encapsulation .

- A process of removing extra information ( i.e header and trailer ) from data on a particular layer is called Decapsulstion .

## 20. The Communication Process - Encapsulation 

* Encapsulation - Process of adding control information as it passes down through the layered model

| Data Link Header | IP Header | TCP Header | HTTP Header | Data | Data Link Trailer |

### I MEDIA

### SERVER

### 01011010
-------------------------------------------------------

                |        HTTP Data          |       |
                                                    |
                |   Data     Data   Data    |       |
                                                    |
                  | Transport Header | Data |       |
                                                    |
 | Network Header | Transport Header | Data |       |
                                                    |
                                                    |
|-------------------------------------------------------|
| Frame   | Network | Transport | Data |    Frame       |
| Header  | Header  | Header    |      |    Header      |
|-------------------------------------------------------|


## 21. The Communication Process - Decapsulation 

* Decapsulation - Process of removing control information as it passes upwards through the layered model .

| Data Link Header | IP Header | TCP Header | HTTP Header | Data | Data Link Trailer |

### Client

### SERVER

-------------------------------------------------------

                |        HTTP Data          |       
                                                    ^
                |   Data     Data   Data    |       |
                                                    |
                  | Transport Header | Data |       |
                                                    |
 | Network Header | Transport Header | Data |       |
                                                    |
                                                    |
|-------------------------------------------------------|
| Frame   | Network | Transport | Data |    Frame       |
| Header  | Header  | Header    |      |    Header      |
|-------------------------------------------------------|


## 22. Binary Maths Introduction 

- Binary It's as easy as 01 , 10 , 11

## 23. Base (Decimal) Number System

Digits (10) : 0 1 2 3 4 5 6 7 8 9

Number of :

        10^4    10^3    10^2    10^1    10^0

       10000's  1000's   100's    10's   1's


3789                3       7       8       9

39                                  3       9

100                      1          0       0

## 24 . Number System Rules 
## 25 . Binary to Decimal Conversion
## 25 . Binary vs Decimal vs Hexadecimal
