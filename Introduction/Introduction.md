# What is System Design?

System Design is the process of defining the architecture, components,modules,interfaces and data flow for a system to meet specific requirements.
it involves making decisions about scalability and reliability,performance and maintainability.
use cases: scalable web apps , distibuted systems, databases and cloud infrastures.

# why system design is important?
scalability and reliability
Architectural thinking
trade off and Decision making: cost , speed and complexity.
Future  Proofing: Prevents bottlenecks and allows smooth evalution of software.

# why networking matters in system design?
- if there is good networking it can improve performances and also will have some low latency.
- networking heps to handle millions of users 
- esential for cloud computing and distributed systems
- if we want to talk btn the client and server networking needs to established well to avoid security bleech.
-  networkig plays a crucial role in 
- - communication
- - security : protecting from unauthorized users.
- - load balancing : distributing traffic to prevent overload on single servers
- - efficiency

 
# Ip Address:
## IPV4
- 32 bit address length eg 196.168.1.1
- dotted decimal notation x.x.x.x x range from 0 to 255
## IPV6
 - 128 bit address length
 - hexadecimal colon notation xxxx.xxxx.xxxx.xxxx.xxxx 
 - scalability: offers more addresses ans  support auto-configuration.
 - IPSec encryption unlike which requires additional configuration.

### why do we need private ip?
ipv4 are limited address . private helps to save public ip addresss and they are not exposed to internet so they are secure.
private ips can be reused within in system.
Organization can assign many private IPs while using single public ips for external communications.

## NAT
- NAT allows multiple devices to share a single IP address
- hides internal ip address 
- nat enables ISP and enterprices to manage large networks with fewer public IPs.

# how load balancer are distributes traffic using IPs.
 ## Dns load balancing:
 - Multiple ips are assigned to domain and DNS helps to direct traffic based on availability and location
 ## layer 4 (Transport layer)
 - Ip addressed and ports
 ## layer 7 Application layer
 - requests are routed based on HTTPs headers and URls and Session data.


#DNS resolutio
client www.example.com
client request ip for domain
first checks in cache and otherwise query is forwarded.
now TLD(Top-level domain) server It points your device to authoritative name sever which is responsible for that specific website
authoritative server provides the exact IP addeess allowing the browser to load

