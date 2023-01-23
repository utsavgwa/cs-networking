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
    - host (end system)
      - eg. computer, desktop, laptop, phone, security system, etc..
    - connecting device
      - eg.
        - router (which conect network to other networks)
        - switch (which connects devices together)
        - modem (which changes the form of data)
  - devices in network are connected using wire or wireless transmission media (cable, air, wifi)

2. **_What are different types of Network Criteria?_**

   1. **Performance**

   - performance is measured on many ways, including transit time and response time.

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
     - implementing policies and procedures for recovery for recovery from breaches and data losses

3. **_What are some types of Network attributes?_**
4. Types of connection-


    - a network is two or moredevices conected through links.
    - a **link** is a comunication pathway that transfers data from one point to another
    - there are two possible types of connections:
      1. point-to-point:
      2. multipoint:
