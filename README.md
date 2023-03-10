# Networking bullets points:

<!-- data communication subtopic 1 -->

1. **_What is Data Communication? (Introduction)_**

- we can say

  - **telecommunication** - means communication at distance.
  - **data** - information represented in any form agreed by parties creating and using it.
  - so, **data communication** - exchange of data between two devices via some form of transmission medium. (eg. wire cable, wi-fi)

- Effectiveness of Data Communication System depends on -
  1. **Delivery**
     - system must deliver data to correct destination.
     - data must be recieved by intended user.
  2. **Accuracy**
     - system must deliver correctly.
     - data altered in transmission is unusable.
  3. **Timeliness**
     - system must deliver data in timely manner.
     - data delivered late is useless.
  4. **Jitter**
     - it means variation in packet arrival time.
     - it is uneven delay in the delivery of audio or video packets.

2. **_What are Components of Data Communication Systems? (5 points)_**
   1. **Message**
      - message is information (data) to be communicated over.
   2. **Sender**
      - sender is the device that sends the data message.
      - eg. computer, telephone, video camera, mobile, etc..
   3. **Reciever**
      - reciever is the device that recieves the message.
   4. **Transmission Medium**
      - it is the physical path by which message travels from sender to reciever.
      - eg.
        - twisted-pair wire
        - coaxial wire
        - fiber-optic cable
        - radio waves
   5. **Protocol**
      - protocol is set of rules that governs data communication.
      - it represents an agreement between communicating devices.
      - without it, devices maybe connected but will not communicate.
      - for eg. french person talking to japanese person.
3. **_What are the types of data, and how it is represented?_**

   1. **Text**

      - represented as bit pattern.
      - various types of bit patterns represent text symbols.
      - a set of bit pattern is called code.
      - process of representing bit pattern is called coding.
      - most famous bit pattern.
        - Unicode (Basic Latin)
          - uses 32 bits.
          - developed by ASCII (American Standards Code for Information Interchange).
          - have 127 characters.

   2. **Numbers**

      - represented as bit pattern.
      - ASCII is not used, number is directly converted to binary number.

   3. **Images**
      - represented as bit pattern.

   - but, what is an image?
     - image is composed of matrix of pixels, where each pixel is a small dot.
     - the size of pixel depends on resolution of screen. It can be 1,000 pixels or 10,000 pixels.
   - if image is not B&W, then we increse te scale to 2-bit patterns.
     - 4 level of gray scales -
       - black pixel - 00
       - dark grey pixel - 01
       - light grey pixel - 10
       - white pixel - 11
   - **methods to represent color images**
     - **RGB**
       - here color is made by combination of 3 primary colors:
         - Red
         - Green
         - Blue
       - intensity of each color is measured and a bit pattern is assigned to it.
     - **YCM**
       - here color is made by combination of 3 other primary colors:
         - Yellow
         - Cyan
         - Magenta

   4. **Audio**
      - it is recording or broadcasting of sound or music.
      - audio is continuous, not discrete
   5. **Video**
      - video is recording or broadcasting of a picture or a movie.
      - it can be produced as -
      - a continuous entity
      - combination of images (each a discrete entity)

4. **_How data flows when 2 devices communicate?_**

- there are 3 ways communication can happen-

  1. **Simplex**

     - it uses entire capacity of channel to send data in one direction.
     - in simplex mode, communication is uni-directional (similar to one way street)
     - only 1 from 2 devices can transmit, and other one can recieve.
     - eg. keyboards, monitors

  2. **Half-duplex**

     - in half-duplex transmission the entire capacity of channel is taken over by whichever of two devices is transmitting at the time.
     - in half-duplex mode, each station can both transmit and recieve, but not at same time.
     - when one device is the other can only recieve (similar to one-lane road)
     - eg. walkie talkies, citizen band radios

  3. **Full-duplex**

     - in full-duplex transmission both stations can transmit and recieve simultaenously (similar to two way street with traffic flowing in both directions at the same time)
     - here signals going in one direction share the capacity of the link with signals going in other direction.
     - sharing occurs in two ways
     - link must contain 2 separate transmission paths.
     - capacity of channels is divided between both signals.
     - eg. telephone network

<!-- newtworks subtopic 2 -->

1. **_What is a Network? (Introduction)_**

   - it is interconnection of a set of devices capable of communication.
     - device can be a -
       - **host** (end system)
         - eg. computer, desktop, laptop, phone, security system, etc..
       - **connecting device**
         - eg.
           - router (which conect network to other networks)
           - switch (which connects devices together)
           - modem (which changes the form of data)
     - devices in network are connected using wire or wireless transmission media (cable, air, wifi)

2. **_What are different types of Network Criteria?_**

   1. **Performance**

   - performance is measured in many ways, including transit time and response time.

     - **transit time** - it is the amount of time required for a message to travel from one device to another.
     - **response time** - it is the elapsed time between enquiry and a response.

   - the performance of a network depends on many factors including -
     - the number of users
     - the type of transmission medium
     - the capabilities of connected hardware
     - the efficiency of software
   - performance is evaluated by two networking metrics - (more throughput and less delay)
     - **throughput**
     - **delay**
     - sometimes we need to increase the throughput, but we increase the delay, because of **traffic congestion in network**

   2. **Reliability**

   - network reliability is measured by the frequency of failure, the time it takes a link to recover from a failure, and the network's robustness in a catastrophe.

   3. **Security**

   - network security includes-
     - protecting data from unauthorised access
     - protecting data from damage and development
     - implementing policies and procedures for recovery from breaches and data losses

3. **_What are some types of Network attributes?_**

   1. name types of connections?

      - a network is two or more devices conected through **links**.
      - a **link** is a comunication pathway that transfers data from one point to another (like a line between two points)
      - there are two possible types of connections:
        1. **point-to-point:**
           - point-to-point provides a dedicated link between two devices.
           - the entire capacity of the link is reserved for transmission between those two devices.
           - eg.
             - p2p connections use actual wire, microwave or satellite links.
             - change channel in tv via infrared remote control, we are establishing p2p between tv and remote.
        2. **multipoint:** (multidrop)
           - in multipoint connection, more than two specfic devices share a specific link.
           - the capacity of the channel is shared, either **spatially** or **temporally**.
             - **spatially shared connection** - if several devices can use the link simultaneously.
             - **time shared connection** - if user must take turns.

   2. what is **physical topology**?

      - it refers to the way in which the network has been laid out physically.
      - the topology of a network is the geometric representation of the relationship of all the links and linking devices it connects to one another (nodes).
      - 4 basic topologies are -

        1. **Mesh** topology -
           - this is duplex communication mode.
           - in mesh topology every device has direct point-to-point link to every other device.
           - **dedicated** means the the link carries the traffic between only the two devices it connects.
           - number of physical links in mesh network with **n** nodes.
             - n(n-1)/2 links
           - it is implemented in a limited fashion because it acts as a backbone, connecting the main computers of a hybrid network that can include several other topologies.
           - eg. connection of telephone regional offices.
           - **advantages of mesh topology**-
             1. use of dedicated links, eliminates the traffic problems.
             2. it is robust, if one link is unusable, it does not incapicitate the entire system.
             3. there is the advantage of security and privacy.
             4. point-to-point links make fault identification and fault isolation easy, traffic can be routed to avoid links with suspected problems.
           - **disadvantages of mesh topology**-
             1. there is alot of cabling and number of i/o ports are required.
             2. installation and reconnection are difficult, since every device must be connected to other device.
             3. the sheer bulk of wiring can be greater than the available space.
             4. the hardware required to connect each link can be expensive.
        2. **Star** topology -
           - here each device has a dedicated point-to-point link only to central controller (called **hub**).
           - the devices are not directly linked to one another.
           - unlike **mesh**, start topology does not allow direct traffic between devices.
           - the **controller** acts as a exchange, if one device wants to send data to another, it sends the data to the controller, which then relays the data to another connected device.
           - the star topology is used in LANs.
           - **advantages of star topology**-
             1. it is less expensive than mesh.
             2. in star, each device needs only one link and one i/o port to connect to other devices, this is why it is **easy to install** and **configure**.
             3. far less cabling needs to be housed.
             4. it is robust, if one link fails, only that link is affected. All other links remain active, -> which leads to easy fault identification and fault isolation.
             5. as long as the **hub** is working, it can be used to monitor link problems and bypass defective links.
           - **disadvantages of star topology**-
             1. one big fault is the dependency of the whole topology on one single point, the hub. If hub goes down the whole system is dead.
             2. still more cabling is required in comparison to (ring or bus) topology.
        3. **Bus** topology -

           - bus topology takes multipoint connection approach.
           - here one long cable acts as a **backbone** to link all the devices in a network.
           - nodes are connected to bus (main) cable, by drop lines and taps.
           - **dropline** - connection running between the device and the main cable.
             **tap** - connector that either splices into the main cable or puntures the sheathing of cable to create a contact with metallic core.
           - as signal travels along the **backbone**, some of its energy is transformed into heat, therefore it becomes weak as it travels farther.
           - this is the reason there are only a number of taps a bus can support, and distance between the taps.
           - bus topology was used in design of early LANs.
           - traditional ethernet LAN can still use bus topology, but not popular nowadays.
           - **advantages of bus topology**-
             1. ease of installation.
             2. backbone can be laid in the most efficient path, so less cabling than mesh or star topologies. Only backbone stretches through the entire facility of a place.
           - **disadvantages of bus topology**-
             1. difficult reconnection and fault isolation.
             2. bus is usually designed to be efficient at installation, so it is difficult to add new devices.
             3. signal reflection at the taps can cause degradation in quality.
             4. a fault or break in the main cable (backbone) stops all transmissions. The damaged area send back reflections in origin direction, creating noise in both directions.

        4. **Ring** topology -
           - in ring topology, each device has a dedicated point-to-point connection with only the two devices on either side of it.
           - a signal is passed along the ring in one direction, from device to device until it reaches its destination.
           - each device in the ring incorporates a repeater.
           - ring topology was prevalant in early days when IBM introduced its LAN, token-ring.
           - nowadays due to high speed LAN requirement ring topology is less popular.
           - **advantages of ring topology**-
             1. ring is relatively easy to install. Each device is linked to only its immediate neighbors. To add or delete a device requires changing only two connections.
             2. Fault isolation is simplified. In a ring signal is circulating all times, if onw device does not recieve a signal within a specified period, it can issue an alarm. The alarm alerts the network operator.
           - **disadvantages of ring topology**-
             1. Constraints are media and traffic considerations (maximum ring length, number of devices)
             2. Unidirectional traffic can be disadvantage, in simple ring a break in ring can disable the entire network. To solve this we can use dual ring or switch capable of closing off the break.

<!-- different typr of networks subtopic 3 -->

1. **_what are some examples of different types of networks?_**

   - The criteria of distinguishing one type of network from another difficult and sometimes confusing. So we use criteria such as -
     - size
     - geographical coverage and
     - ownership

   1. **LAN (Local Area Network)**
      - a LAN is usually privately owned
      - limited in size, and
      - connects some hosts in a single office, building or campus.
      - each host in a LAN has an identifier, an address, that uniquely defines the host in the LAN.
      - a **packet** sent by a host to another host carries both the source host's and the destination host's address.
      - in past, all host in network were connected through common cable, which meant that packet sent by one host to another was recieved by all hosts. The intended recipient kept the packet and the others dropped the packet.
      - today most LAN use smart connecting **switch**.
        - switch -
          - switch it recognises the destination address of the packet and guide the packet to its destination without sending to all other hosts.
          - it alleviates the traffic in the LAN, and allows more than one pair to communicate with each other at the same time, if there is no common source and destination among them.
   2. **WAN** (Wide Area Network)
      - a WAN is also an interconnection of devices capable of communication
      - WAN has wide geographical span a town, a state, a country
      - WAN interconnects connecting devices such as **switches**, **routers**, or **modems**
      - WAN is normally created and run by communication companies and leased by an organisation that uses it.
      - two distinct examples of WAN, nowadays are -
        1. **point-to-point WAN**
           - point-to-point WAN is a network that connects 2 communication devices through a transmission media (cable or air)
        2. **switched WAN**
           - switched WAN is a network with more than 2 ends. **switched WAN is used in the backbone of global communication today**.
           - it is a combination of several point-to-point WANs that are connected by **switches**.
   3. **Inter-network**
   4. **Switching**
   5. **The Internet**
   6. **Accessing the Internet**

<!-- History of Internet subtopic 4 -->
