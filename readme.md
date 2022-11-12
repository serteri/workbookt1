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
There are two types of Ip address which are static IP address and dynamic IP address.

1. Static dynamic address: It never changes. It provides a simple and reliable way of communication.

**Routers and routing:**
A router is a device. This device can connect, route for network packets according to their address. Routers use packets which contain different kinds of data such as images,files, simple transmissions.

It is designed to receive ,analyse and forward packets between computer networks.(5) A router is like a traffic controller at the airports. You can think data packets as aircrafts headed to different airports in this case networks. Each aircraft has a destination different airports just like each packet data. They needed to be guided by traffic controller, just like data packets are guided by routers.(6)

Routing is the progress of choosing a direction over one or more networks. The basis of routing can implement to any kind of network.(7) It defines directions for IP-packet traffic between networks or within networks.(8) That defines the process of sending a packet data from source to target destination. It uses the Internet Protocols (IP) to travel one destination to the another destination. When router collect a packet data ,it interprets the **headers** of the packet to find out its predetermined destination. There are three types of routing: static routing, default routing and dynamic routing.

1. Static routing: Routes are manually added to the routing table. It does not need to determine bandwith usage between routers.

2. Default routing: All packets is configured and send toward a single router. Stub router is commonly used for this type of routing.
3. Dynamic routing: Modifications are automatically made depends on the present state of the route in the routing table. It practices **protocols** to explore network target destinations and the routes to attain it. (9)

## References

1. [Semrush](https://www.semrush.com/blog/markup-language/)

2. [Hackr.io](https://hackr.io/blog/what-is-markup-language)
3. [Wpamelia](https://wpamelia.com/markup-languages/)
4. [Cloudflare](https://www.cloudflare.com/en-gb/learning/network-layer/what-is-a-packet/)

5. [wpbeginner](https://www.wpbeginner.com/glossary/ip-address/)

6. [Javapoint](https://www.javatpoint.com/router)

7. [Cloudflare](https://www.cloudflare.com/en-gb/learning/network-layer/what-is-a-router/)

8. [Cloudflare](https://www.cloudflare.com/en-gb/learning/network-layer/what-is-routing/)

9. [Cisco](https://www.cisco.com/c/en/us/products/routers/what-is-routing.html)

10. [webopedia](https://www.webopedia.com/definitions/routing/)
