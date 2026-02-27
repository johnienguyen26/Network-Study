# The OSI MODEL
## What is the OSI MOdel?
  - Opens Systems Interconnection Reference Model
  - It's a guide, that's why it's coined the term "model"
  - There are unique protocols at every layer
  - ACRONYM "All People Seem to Need Data Processing" APSTNDP.
## Layer 1 - Phyiscal Layer
  - Signaling, cabling, connectors
  - This layer isn't about protocols
## Layer 2 - Data Link
  - The basic netowork "Language"
    - The foundation of communication at the data link layer
  - Data Link Control (DLC) protocols
    - MAC (Media Access Control) address on Ethernet
  - The "Switching" layer
## Layer 3 - Network Layer
  - The "Routing" layer
  - Internet Protocol(IP)
  - Fragments frames to traverse different networks
## Layer 4 - Transport Layer
  - The "Post Office" layer
    - Parcels and letters
  - TCP (Transmission Control Protocol)
  - UDP (User Datagram Protocol)
## Layer 5 - Session Layer
  - Communication management between devices
    - Start, stop, restart
  - Control protocols, tunneling protocols
## Layer 6 - Presentation Layer
  - Character encoding
  - Application encryption
  - Often combined with the Application Layer
## Layer 7 - Application Layer
  - The layer we see
  - HTTP, FTP, DNS, POP3

## EXAMPLES:
<img src="images/osi model.png" width="125" align="left">

### Your Eyes
### Application encryption (SSL/TLS)
### Control protocols, tunneling protocols
### TCP segment, UDP datagram
### IP Address, Router, Packet
### Frame, MAC address, Extended Unique Identifier(EUI-48, EUI-64), Switch
### Cables, fiber, and the signal itself
##
<img src="images/osi model.png" width="125" align="left">


### Application: https://mail.google.com
### Presentation: SSL Encrpytion
### Session : Link the presentation to the transpot
### Transport: TCP encapsulation
### Network: IP encapsulation
### Data-link: Ethernet
### Phyiscal: Electrical signals
##
