# Computer Network

> This intended to provide some outline on keypoint to revise, but is definitely not exhaustive. There may be mistakes due to my end and corrections are welcome.

This lecture takes a 'layer wise' approach that focusing on each layer of the network system, and sometimes discuss how each of them interact with others. The recommended textbook is still the classical *Computer Network: A Top-Down Approach*, you can check most of the details for protocols and implementations that was skipped or blurred in the lectures.

## Topic 1: Introduction

This topic is mostly concept only and suggests to have basic understanding

* Concepts of Different Switching
  * Packet Switching V. Circuit Switching
  * TDM V. FDM

## Topic 2: Architecture and Layer

This topic is mostly concept only and suggest to have basic understanding

* Layering
  * OSI 7 layers V. TCP/IP 5 layers stack
  * Effect of Layering(advantages/disadvantages)
* Philosophy of Internet
  * Different registry, e.g. IANA, ITU
  * Different Protocols (and RFCs)
  * Different ISPs
  * Confederated unions of nodes

## Topic 3: Physical Layer and Datalink Layer

This topic contains algorithms and concept that requires detail understanding

* physical medias
  * different encodings, e.g. NRZ, NRZI, Manchester, Quad Level
  * concepts of baud rate and bit rate
  * different medias, e.g. cooper wire(twisted pairs), fibres, radio signal, coaxial cables, etc.
* Media Access Control Protocols(MAC)
  * ARP protocols
* CDMA and collision avoidance
  * how they are used in practice
  * hidden terminal/exposed terminal
* Ethernet
  * packet structure
  * Wired (switch based)
  * Wireless(802.11x)
* Error Correction V. Error Detection
  * parity bits V. checksum

## Topic 4: Network Layer

This topic contains algorithms and concept that requires detail understanding

* Router protocols
  * distance vector v. Link state routing
* Routing tables
  * how they recompute and how are they resilliance
* Router V. Switch
  * Router’s control plane and data plane
* IP address
  * IPV4 protocols V. IPV6 protocols
  * IP packet structure
  * sending between V4 and V6
* DNS
  * DNS entry in V4 and V6
  * How DNS work
  * DNSSEC and DoH
* NAT, subnet
  * different type of NAT
  * how subnet and subnet mask works
* DHCP
  * Protocols 
  * pros and cons
  * alternative method in IPV6

## Topic 5: Transport Layer

This topic contains algorithms and concept that requires detail understanding

* TCP v. UDP
  * difference between TCP and UDP
  * concept of ARQ
* TCP details
  * checksum and timeout
  * sliding windows 
  * flow control
  * congestion control: exponential slow start, AIMD, Congestion avoidance and fast retransmit
  * 3 times hand shake
  * teardown
  * different type of connection(sequential/pipeline, persistent/non-persistent)

## Topic 6: Application Layer

This topic contains algorithms and concept that requires detail understanding

* HTTP protocol
* DNS server
* FTP/RTP(basic understanding)
