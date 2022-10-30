# ComputerNetwork
Every details covered at one place

**Computer Network means an interconnection of autonomous (standalone) computers for information exchange. The connecting media could be a copper wire, optical fiber, microwave, or satellite.**

**An interconnection of multiple devices, also known as hosts, that are connected using multiple paths for the purpose of sending/receiving data or media. Computer networks can also include multiple devices/mediums which help in the communication between two different devices; these are known as Network devices and include things such as routers, switches, hubs, and bridges.**

****Open system:**** A system which is connected to the network and is ready for communication. 

****Closed system:**** A system which is not connected to the network and can’t be communicated with.

🔆 Network Topology: The layout arrangement of the different devices in a network.Eg: Bus, Star, Mesh, Ring, and Daisy chain. 

🔆 OSI: stands for Open Systems Interconnection is a reference model that specifies standards for communications protocols and also the functionalities of each layer.

🔆 Protocol:is the set of rules or algorithms which define the way how two entities can communicate across the network and there exists different protocol defined at each layer of the OSI model. eg of protocols are TCP, IP, UDP, ARP, DHCP, FTP and so on.

**UNIQUE IDENTIFIERS OF NETWORK** `Host name`, `IP Address (Internet Protocol address)`, `MAC Address (Media Access Control address)`, `Port`, `DNS Server`, `Socket`, `ARP`, `RARP`.

💢 Host name: Each device in the network is associated with a unique device name known as Hostname. Type “hostname” in the command prompt(Administrator Mode)

💢 IP Address (Internet Protocol address) also known as the Logical Address, is the network address of the system across the network. To identify each device in the    world-wide-web, the Internet Assigned Numbers Authority (IANA) assigns an IPV4 (Version 4) address as a unique identifier to each device on the Internet. 
The length of an IPv4 address is 32-bits, hence, we have 2^32 IP addresses available. The length of an IPv6 address is 128-bits.

💢 A port can be referred to as a logical channel through which data can be sent/received to an application. Any host may have multiple applications running, and each of these applications is identified using the port number on which they are running. A port number is a 16-bit integer, hence, we have 2^16 ports available.

💢 Media Access Control address) also known as physical address, the MAC Address is the unique identifier of each host and is associated with its NIC (Network Interface Card). A MAC address is assigned to the NIC at the time of manufacturing.The length of the MAC address is : 12-nibble/ 6 bytes/ 48 bits 

💢 Socket: The unique combination of IP address and Port number together are termed as Socket. 
RARP stands for Reverse Address Resolution Protocol provides the IP address of the device given a physical address as input. But RARP has become obsolete because of DHCP

💢 ARP stands for Address Resolution Protocol used to convert an IP address to its corresponding physical address(i.e., MAC Address) and also used by the Data Link Layer to identify the MAC address of the Receiver’s machine. 

💢 DNS Server(domain Name system) is basically a server which translates web addresses or URLs (ex: www.google.com) into their corresponding IP addresses.Don’t need to remember all the IP addresses of each and every website. The command ‘nslookup’ gives you the IP address of the domain you are looking for & also provides the information of our DNS Server.

## URI: 
- stands for ‘Uniform Resource Identifier’. A URI can be a name, locator, or both for an online resource whereas a URL is just the locator. URLs are a subset of URIs.  - A URL is a human-readable text that was designed to replace the numbers (IP addresses) that computers use to communicate with servers.
- A URL consists of a protocol, domain name, and path (which includes the specific subfolder structure where a page is located) like-

       `protocol://WebSiteName.topLevelDomain/path`
~ Protocol – HTTP or HTTPS.
~ WebSiteName – google etc.
~ topLevelDomain- .com, .edu, .in etc.
~ path- specific folders and/or subfolders that are on a given website.

💭 Who governs the Internet? 
- ISOC is a voluntary membership organization whose purpose is to promote global information exchange through Internet technology. 
-  
- ISOC appoints the IAB- Internet Architecture Board. They meet regularly to review standards and allocate resources, like addresses.
IETF- Internet Engineering Task Force. Another volunteer organization that meets regularly to discuss operational and technical problems. 

***IoE is the intelligent connection of people, processes, data, and things that will be transforming our world in such a way that there will be billions of connected devices having sensors to detect, measure and access their status all of which will be connected over a public or private network built over standard protocols like TCP/IP.*** 
💭 Difference btween IOT & IOE

## 1.6 Goals of Networks
Networking Elements – The computer network includes the following networking elements: 

`At least two computers` 
`Transmission medium either wired or wireless `
`Protocols or rules that govern the communication `
`Network software such as Network Operating System `

Network Criteria: The criteria that have to be met by a computer network are: 
1. Performance – It is measured in terms of transit time and response time. 
2. Reliability – It is measured in terms of `Frequency of failure`, `Recovery from failures`, `Robustness during catastrophe`.
3. Security – It means protecting data from unauthorized access.  

Goals of Computer Networks: The following are some important goals of computer networks:  

1.Resource Sharing – 
Many organization has a substantial number of computers in operations, which are located apart. Ex. A group of office workers can share a common printer, fax, modem, scanner, etc. 
 
2.High Reliability – 
If there are alternate sources of supply, all files could be replicated on two or more machines. If one of them is not available, due to hardware failure, the other copies could be used. 
 
3.Inter-process Communication – 
Network users, located geographically apart, may converse in an interactive session through the network. In order to permit this, the network must provide almost error-free communications. 
 
4.Flexible access – 
Files can be accessed from any computer in the network. The project can be begun on one computer and finished on another. 
Other goals include Distribution of processing functions, Centralized management, and allocation of network resources, Compatibility of dissimilar equipment and software, Good network performance, Scalability, Saving money, Access to remote information, Person to person communication, etc. 

## 1.7 Line Configuration in Computer Networks

For communication to occur, two devices must be connected in some way to the same link at the same time. There are two possible types of connections: 

✨ Point-to-Point Connection
✨ Multipoint Connection

Terms in Multipoint Connection:

🎶 Spatial Sharing: If several devices can share the link simultaneously, it’s called Spatially shared line configuration. 
🎶 Temporal (Time) Sharing: If users must take turns using the link, then it’s called Temporally shared or Time Shared Line configuration. 

## 1.8 Transmission Modes in Computer Networks (Simplex, Half-Duplex and Full-Duplex)

Transmission mode means transferring data between two devices. It is also known as a communication mode. Buses and networks are designed to allow communication to occur between individual devices that are interconnected. There are three types of transmission mode:-`Simplex`, `Half-Duplex` & `Full-Duplex`
## 1.9 Types of Transmission Media

Transmission medium is a physical path between the transmitter and the receiver i.e. it is the channel through which data is sent from one place to another.Classified as 1. Guided Media: It is also referred to as Wired or Bounded transmission media. Signals being transmitted are directed and confined in a narrow pathway by using physical links. Features:  `High Speed` `Secure` `Used for comparatively shorter distances`
types:1.Twisted Pair Cable-Unshielded Twisted Pair (UTP)
                        -Shielded Twisted Pair (STP)
      2.Coaxial Cable 
      3.Optical Fiber Cable 
      4.Stripline
      5.Microstripline
      
2. Unguided Media: 
It is also referred to as Wireless or Unbounded transmission media. No physical medium is required for the transmission of electromagnetic signals. 
Features: `The signal is broadcasted through air` `Less Secure` `Used for larger distances`
types: 1.Radio waves-Further Categorized as (i) Terrestrial and (ii) Satellite. 
       2.Microwaves
       3.Infrared
       
## 1.10 Difference between Unicast, Broadcast and Multicast in Computer Network


## 1.11 Introduction to basic Networking Terminology

- LANs (Local Area Networks)
- MANs (Metropolitan Area Networks)
- WANs (Wide Area Networks)

## 1.12 Types of Network Topology
### Mesh Topology
### tree Topology
### Star Topology
### Hybrid Topology
### Ring Topology
### Bus Topology
## 1.13 Types of area networks – LAN, MAN and WAN

![LAN](https://user-images.githubusercontent.com/90051406/198874289-7a1cfd7f-b8f1-4589-a45b-5a2cc5ba2709.png)

There are other types of Computer Networks also, like : 
 

- PAN (Personal Area Network)
- SAN (Storage Area Network)
- EPN (Enterprise Private Network)
- VPN (Virtual Private Network)
Conclusion –

There are many advantages of LAN over MAN and WAN, such as LAN’s provide excellent reliability, high data transmission rate, they can easily be managed and shares peripheral devices too. Local Area Network cannot cover cities or towns and for that Metropolitan Area Network is needed, which can connect a city or a group of cities together. Further, for connecting a Country or a group of Countries one requires a Wide Area Network.

## 1.14 Telecom Networks

Telecom networks are mostly used today for wide-area communication. Stringing a wire between every pair of telephones that might want to communicate was not a good long-term strategy. A better idea was to connect all the telephones to a central switching office. There an operator could connect one telephone to another via a switchboard. 

Routing a telephone call
- Connection-Oriented Services – I
- Transmission Media in Telephone Systems
- The local loop
- Signaling
- Control Plane Protocol Stack in SS7
- Digital Technology in Telephone Networks

## 1.15 Access networks

An access network is a type of network which physically connects an end system to the immediate router (also known as the “edge router”) on a path from the end system to any other distant end system. Examples of access networks are ISP, home networks, enterprise networks, ADSL, mobile network, FITH etc.

Types of access networks:`Ethernet `, `Digital Subscriber Line`,`FTTH `,`Wireless LANs `, `3G and LTE `.
`
## 1.16 TCP/IP Model
![OSI](https://user-images.githubusercontent.com/90051406/198879909-0411c409-a2d2-42ba-9b84-ae6c5869a30c.png)

OSI layers are:
1.Process/Application Layer
2.Host-to-Host/Transport Layer
3.Internet Layer
4.Network Access/Link Layer

## 1.17 Layers of OSI Model


## 1.18 Introduction to Active Directory Domain Service
***A directory is a hierarchical structure that stores information about objects on the network. A directory, in the most generic sense, is a comprehensive listing of objects. A phone book is a type of directory that stores information about people, businesses, and government organizations. Phone books typically record names, addresses, and phone numbers.***

Active Directory (AD) is a Microsoft technology used to manage computers and other devices on a network. It is a primary feature of Windows Server, an operating system that runs both local and Internet-based servers.

Benefits of Active Directory –

- Hierarchical organizational structure.
- Multimaster Authentication & Multimaster replication (the ability to access and modify AD DS from multiple
- points of administration)
- A single point of access to network resources.
- Ability to create trust relationships with external networks running previous versions of Active Directory and even Unix.

## 1.19 Advantages and Disadvantages of Computer Networking

# 2.Data Link Layer
## 2.1 Local Area Network (LAN) Technologies.
## 2.2 Computer Network | Bridges (local Internetworking device)
## 2.3 Internetworking
## 2.4 Framing In Data Link Layer
## 2.5 Introduction of MAC Address
## 2.6 MAC Filtering
## 2.7 Multiple Access Protocols
## 2.8 Ethernet Frame Format
## 2.9 EtherChannel
## 2.10
## 2.11
## 2.12
## 2.13
## 2.14
## 2.15
## 2.16
## 2.17
## 2.18
## 2.19
## 2.20
## 2.21
## 2.22
## 2.23
## 2.24
## 2.25
## 2.26
## 2.27
## 2.28
## 2.29
## 2.30
## 2.31
## 2.32
## 2.33
## 2.34
## 2.35
## 2.36
## 2.37
## 2.
## 2.
## 2.
v## 2.
## 2.
## 2.
