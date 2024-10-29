### Resources
- [CTFD](http://10.50.23.214:8000)

# Network Access
### Stuff to Know
- understand headers

## OSI Model
1. Physical
    - What is actually transmitting the data
2. Data Link
    - Implements frames
    - 802.11, Ethernet, Bluetooth
3. Network
    - How networks talk
    - IP is implemeted at this layer (both IPv4 and IPv6)
    - ICMP, IPSec, and Routing protocols are on this layer as well
4. Transport
    - TCP and UDP reside at this layer
    - Headers that contain information added to the packet
    - Ports are implemented at this layer
5. Session
    - Maintains a connection
    - Earliest of the upper 3 layers
6. Presentation
    - Encryption and compression
    - File extentions happen at this layer (.exe, .jpg, .mp3)
7. Application
    - Actually using the data with a specific application

## Ways information is represented
- Binary
    - Base2 (0 and 1)
    - Bit is the base, 8 Bits = 1 Byte
    - 4 Bits = Nibble, 16 Bits = Half word, 32 Bits = Word
- Hexadecimal
    - Base16 (0-9 a-f)
    - A number formatted 0x(number) indicated hexidecimal
    - 1 digit in Hex is equivalent to a Nibble
- Base64
    - uses 64 symbols
    - Uses (=) to represent a null value

## Network Topologies
- Bus
    - Everything is on one main cable
- Star
    - All devices are plugged in to a central hub
    - One single ingress/egress point
- Ring
    - Data travels in one direction in a ring
- Mesh Network
    - Full mesh - every device is connected to every other
    - Partial mesh - all devices can talk to each other, but are not all directly connected
- Wireless LAN
    - You can transfer from on Access Point to another by moving to a different area
    - Divided into zones
- Heirarchical
    - Has layers to the network
    - Access Layer
    - Distribution Layer
    - Core Layer

