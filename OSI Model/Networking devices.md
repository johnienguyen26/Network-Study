# Networking Devices
  - Many different ways to forward traffic
    - A data center full of equipment
  - Every device have a purpose
    - The implementation may change over time
    - Once installed, it can often be difficult to remove
  - There are new technologies all the time

## Router
  - Routes traffic between IP subnets
    - OSI layer 3 device
    - Routers inside of switches sometimes called "layer 3 switches"
    - Layer 2 = Switch
    - Layer 3 = Router
### Often connects diverse network types:
  - LAN, WAN, copper, fiber
## Switch
  - Bridging done in hardware
    - Application-specific integrated circuit (ASIC)
  - An OSI layer 2 device
    - Forwards traffic bhased on data link address
  - Many ports and features
    - The core of an enterprise network
    - May provide Power over Ethernet (PoE)
  - Multilayer switch
    - Includes Layer 3 (routing) functionality
## Firewalls
  - FIlter traffic by port number or application
    - Traditional vs. NGFW (Next Generation Firewall)
  - Encrpyt Traffic
    - VPN between sites
  - Most firewalls can be later 3 devices(Routers)
    - Often sits on the ingress/egress of the network
    - Network Address Translation (NAT)
    - Dynamic Routing
## IDS and IPS
  - Intrustion Detection System / Intrustion Prevention System
    - Watch network traffic
  - Intrustions
    - Exploits against operating systems, applications, etc.
    - Buffer overflows, cross-site scripting, other vulnerabilities
  - Detection vs. Prevention
    - Detection: Alarms or alerts
    - Prevention: Stop it before it gets into the network
## Balancing the load
<img src="images/load balancer.png" width="300" align="right">

  - Distribute the load
    - Multiple servers
    - Invisible to the end-user
  - Large-scale implementations
    - Web server farms, database farms
  - Fault tolerance
    - Server outages have no effect
    - Very fast convergence 
  - Configurable load
    - Manage across servers
  - TCP offload
    - Protocol overhead
  - SSL offload
    - Encryption/Decryption
  - Caching
    - Fast response
  - Prioritization
    - QoS
  - Content switching
    - Application-centric balancing

## Proxies
  - Sits the between the users and the external network
  - Receives the user requests and sends the request on their behalf (the Proxy)
  - Useful for caching information, access control, URL filtering, content scanning
  - Applications may need to know how to use the proxy (explicit)
  - Some proxies are invisible (transparent)
## NAS vs. SAN
  - Network Attached Storage (NAS)
    - Connect to a shared storage device across the network
    - File-level access
  - Storage Area Network (SAN)
    - Looks and fells like a local storage device
      -  Block-level access
    - Very efficient reading and writing
  - Requires a lot of bandwidth
    - May use an osilated network and high-speed network technologies
## Access Point (AP)
  - Not a wireless router
    - A wireless router is a router and an access point in a single device
  - An access point is a bridge
    - Extends the wired network onto the wireless network
    - OSI Layer 2 device
## Wireless networks everywhere
  - Wireless networking is pervasive
    - you probably don't just have a single access point