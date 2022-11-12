# Question 1

**Identify** and **explain** common and important components and concepts of web development markup languages?

_Answer:_

First of all we need to define what _mark-up_ language is.
A markup language is a human-readable language that is used by computer.

There are different mark-up languages. Some of markup languages are HTML (Hypertext Markup Language) , KML (Key whole Markup Langunage) , MathML(Mathematical Markup Langunage) , SGML(Standard Generalized Markup Language) ,XML(eXtensible Markup Language), XHTML(eXtensible Hypertext Markup Language). Most commomly used in the world is HTML.

There is one thing is common for all mark-up languages which they all use of tags. For instance < >. What inside in brackets is represented by the formatted content. Tags come in pairs,one is opening and the other one is closing.(1) For example

```html
<p></p>
```

But some of tags are self-closign tags.For example

```html
<img />
<input />
<br />
<area />
```

Whatever inside between tags can be modified by the formatting. You can modify the text between tags for exampe you can make them bold or italic or you can change font-family,font-size etc...  
There is also element in Markup languages. Element is like tag but extented. An element includes tags as well as what is written between them. For example:

```html
<p>Hello World!</p>
```

Mark-up languages are easy to read. Anyone can understand most of the content.  
Markup languages have set of rules. These rules define to how to use tags. These set of rules allow for consistent and structured document.(2)
Markup languages are not as stirct as programming languages. For example if something wrong in the document, you can not get any complier error like you get programinnig languages.(3)

# Question 2

**Define** the features of the following technologies that are essential in terms of the development of the internet:

- packets
- IP addresses (IPv4 and IPv6)
- routers and routing
- domains and DNS

Explain how each technology has contributed to the development of the internet.

_Answer:_

Defition of the technologies in the question:

- Packets: Data is sent as a package through internet and then these packets are recombined by the computer. For example a user needs to load a file. The file is sent piece by piece from web server. It is called packets of data.And then reseamblied it by the user's computer.(4)

Packets are made of a header and a payload. The header is the data used by networking hardware. The payload is extracted and used by an operation systems, application software or higher layer protocols. Each packet contains a destination address on the network, so routers known where forward them.

**IP address(IPv4 and Ipv6)**

Computers accross the globe to each other in a cirtual space, this invention was called tranmission control protocol(TCP) which was followed bt Internet Protocol(IP). This protocol made it possible for computers on different networks to communicate each other. It is an exclusive address that determines a device on the internet or local network.(5)
There are two types of Ip address which are static IP address and dynamic IP address.(6)

1. Static dynamic address: It never changes. It determines a straightforward and stable way of communication.
2. Dynamic IP address: These are the interim Ip addresses. Each time a computer connected to internet an IP address changes accordingly.There is a pool of IP address and these IP address borrowed from there.

_IP version 4 and IP version 6_ (7)

At the moment there are two types of IP address running which are IP version 4(IPv4) amd IP version 6 (IPv6). There are many aspects with there two types. It was planned to take over the IPv4. It used 128-bit address and supports 2128 i.e. rougly 3.4 X 1038 address.

**IP version 6**

This it the most recent version of IP. It was established by the Internet Engineering Task Force (IETF).

**The feature of IPv6**

1. IPv6 brings improved the ability end-to-end connections than IPv4.
2. It provides faster routing.
3. It contributes more security for applications and networks
4. IPv6 purseus the main design fundamentals of IPv4 and so that the changeover from IPv4 to IPv6 is effortless.
5. The administration is easier than IPv4.
6. Improved flexibility aspects than IPv4.

**IP version 4**

IP Version 4 (IPv4) was described in 1981. It has not changed a lot since that date but in this time, there is a high demand of IP address than IPv4 could supply.

IPv4 runs 32-bit IP address. So the total of IP address is around 4,294,967,296.

An IPv4 address is commonly setup as four 8-bit fields. Each 8-bit field produces a byte of the IPv4 address. There are two parts :the network part and the host part.

The network part represent an unique number for your network. and also describes the class of network.
The host part is a part of IPv4 address is assigned to each host.It describes the computer or device on the network. There are total five classes of IPv4:

1. Class A address : The class A address only consists of IP starting from 1.x.x.x to 126.x.x.x.
2. Class B address : The class B IP Addresses starts from 128.0.x.x to 191.255.x.x. First two digits in the two bits are set to zero.
3. Class C address : Class C address starts 192.0.0 to 223.255.255.x.
4. Class D address : The IP address starts from 224.0.0.0 to 239.255.255.255.
5. Class E class : The Ip address starts from 240.0.0.0 to 255.255.255.254.

**Routers and routing:**
A router is a device. This device can connect, route for network packets according to their address. Routers use packets which contain different kinds of data such as images,files, simple transmissions.

It is designed to receive ,analyse and forward packets between computer networks.(8) A router is like a traffic controller at the airports. You can think data packets as aircrafts headed to different airports in this case networks. Each aircraft has a destination different airports just like each packet data. They needed to be guided by traffic controller, just like data packets are guided by routers.(9)

Routing is the progress of choosing a direction over one or more networks. The basis of routing can implement to any kind of network.(10) It defines directions for IP-packet traffic between networks or within networks.(11) That defines the process of sending a packet data from source to target destination. It uses the Internet Protocols (IP) to travel one destination to the another destination. When router collect a packet data ,it interprets the **headers** of the packet to find out its predetermined destination. There are three types of routing: static routing, default routing and dynamic routing.

1. Static routing: Routes are manually added to the routing table. It does not need to determine bandwith usage between routers.

2. Default routing: All packets is configured and send toward a single router. Stub router is commonly used for this type of routing.
3. Dynamic routing: Modifications are automatically made depends on the present state of the route in the routing table. It practices **protocols** to explore network target destinations and the routes to attain it. (12)

**Domains and DNS**

Domain or domain name is the location of a website. Every website has an IP address.It is good for computers but it is kind of difficult to remember it. That's why we use domain names instead of IP address. A domain name can have up to 63 characters.

![domain name exmaple](./images/domain_1.png)(13)

An URL (complete web address) consists of different parts : protocol,domain name (includes subdomain,seceon-level domain,top-level domain),subdirectory,path.

On the example above:

Protocol:https://
domain name:blog.hubspot.com
subdomain:blog
second-level domain:hubspot
top-level domain:.com
subdirectory: /website
path:/what-is-a-domain

![anatomy of a Web Address](./images/Anatomy%20of%20a%20web%20address.png)(14)

![url overview](./images/domain.png)(15)

DNS is the domain name system. It is like the phonebook of the Internet.(16)

DNS converts domain names to IP address so Internet resources can be loaded by browsers. Computers and machines do not understand domain names so it needed to be converted to numerical values.

# Question 3

**Define** the features of the following technologies that are essential in terms of the development of the internet:

- TCP
- HTTP and HTTPS
- web browsers (requests, rendering and developer tools)

Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)

**Answer**

TCP(Transmission Control Protocol): It is a communication standard. It permits application programs and computers or devices to swap messages over a network.(17) In the digital network, this protocol is one of the most frequently used protocols. TCP construts a data and the data can be sent between a client and a server. It solves many problems such as lost packets,out of order packets, duplicate packets and damaged packets.(18)

It is a stable protocol. It provides flow control.It determines that the data arrives the legitimate destination in the correct order that it was sent.
TCP can reduce the speed of the network because it runs several layers.No changing made since its first development around 30 years ago.(19)

![TCP](./images/tcp2.png)(19)

HTTP and HTTPS:
HTTP is the hypertext Transfer Protocol. it is the foundation of the World Wide Web(www). It is an application layer protocol. It is a request-response protocol for the web.(20)

It was created to implement smooth communicate between devices and applications on the web.(21) There are two sides client and server.Client sends a request to the server. Server reponds the request with a status line or error code.(22)

![http](./images/htpp.gif)(22)

HTPPS: This is a secure version of HTTP. It is the primary protocol used to send data between a web browser and a website.

It is encryted to increase the security of data transfer.(23)

It is used a protocol called Transport Layer Security(TLS). It is important because it avoids websites from having their information transmit easily access or viewed by anybody sneaking on the network.

## References

1. [Semrush](https://www.semrush.com/blog/markup-language/)

2. [Hackr.io](https://hackr.io/blog/what-is-markup-language)
3. [Wpamelia](https://wpamelia.com/markup-languages/)
4. [Cloudflare](https://www.cloudflare.com/en-gb/learning/network-layer/what-is-a-packet/)

5. [wpbeginner](https://www.wpbeginner.com/glossary/ip-address/)

6. [interserver](https://www.interserver.net/tips/kb/types-features-classes-ip-address/)

7. [interserver](https://www.interserver.net/tips/kb/types-features-classes-ip-address/)

8. [Javapoint](https://www.javatpoint.com/router)

9. [Cloudflare](https://www.cloudflare.com/en-gb/learning/network-layer/what-is-a-router/)

10. [Cloudflare](https://www.cloudflare.com/en-gb/learning/network-layer/what-is-routing/)

11. [Cisco](https://www.cisco.com/c/en/us/products/routers/what-is-routing.html)

12. [webopedia](https://www.webopedia.com/definitions/routing/)

13. [blog.hubspot](https://blog.hubspot.com/website/what-is-a-domain)

14. [blog.hubspot](https://blog.hubspot.com/website/what-is-a-domain)

15. [computerhope](https://www.computerhope.com/jargon/d/domain.htm)

16. [Cloudflare](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)

17. [fortinet](https://www.fortinet.com/resources/cyberglossary/tcp-ip)

18. [khanacademy](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet/xcae6f4a7ff015e7d:transporting-packets/a/transmission-control-protocol--tcp)

19. [geeksforgeeks](https://www.geeksforgeeks.org/what-is-transmission-control-protocol-tcp/)

20. [Cloudflare](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/)

21. [paessler](https://www.paessler.com/it-explained/http)

22. [tutorialspoint](https://www.tutorialspoint.com/http/http_overview.htm)

23. [cloudflare](https://www.cloudflare.com/en-gb/learning/ssl/what-is-https/)
