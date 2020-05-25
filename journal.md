# Journal for Unit 4

## Week 34 - 20 May 2020

### What did I do
* Javascript practice
  * In combination with HTML websites, and CSS
* Python practice (codin games)
  * Chuck norris game
  * Defibrillators
* IA preparations
  * Brainstorm ideas for topics
  * Meeting with Dr. Pinzon
  * Created IA repository, added files of the 5 criterias

### What did I learn
* Embedding Javascript in HTML websites
* Importing libraries for Javascript/HTML
* Manipulating elements with Javascript
* How to convert ascii strings to binary strings in Python
* Calculating distance between coordinates
* Choosing an IA topic, and the importance of clarifying your topic early

### To-do list
* Work on IA over summer

**Summary for "Computer Networks" video:**
First networks from 1950s and 60s. Replaced sharing of physical documents and resources. The most successful LAN implementation was Ethernet, which is a system where all computers are connected to one cable. When data is transmitted, only the computer with the correct address - MAC address - receives the information. The same applies to WiFi, where only the carrier is changed; from copper wires in cables to radiowaves in the air. The rate at which data can be transmitted is called bandwidth. A problem called collisions can arise - when two computers on the same network of ethernet cables try to transmit at the same time. The solution is for computers to detect such colisions, wait for a random period of time, and then try again. If it collides again and again, the wait time is increased every time by a factor of 2.

To minimize the chance of transmission collisions multiple ethernet cables can be used. Each ethernet cable is called a collision domain. Increasing the number of ethernet domains, switches can be used. Switches separate the domains and only transmits accross if necessary. This is possible because the switch knows which computers are on which domain. However, with the rise of the internet, finding the shortest possible distance between two devices is critical. This is called routing. 

The simplest way to connect two devices is to allocate a dedicated line for their exclusive use. This is both inflexible and expensive. This approach is called circuit switching. Another approach is message switching; instead of information travelling directly from A to B, it goes through several stops. The number of hops a message does is called the hop count. This is useful because it can identify routing problems. The hop count is stored with the message and updated along its journey. A problem with this arises when sending bigger files. This can clog up paths for a long period of time. This is solved by dividing the whole message into smaller pieces, called packets. Each packet contains a destination address, defined by the "Internet protocol" (IP).

With the huge amounts of data being transferred over the internet all the time, bottlenecks can appear and disappear in milliseconds. Network routers always try to balance the load across multiple routes, to minimize delay. This is called congestion control. Chopping up data into smaller packets and sending these along flexible routes is the foundation for the internet today, and is called Packet Switching. To ensure that messages are exchanged seamlessly, every router and data transmitter follow certain universal protocols (specific rules). 

Today there is an estimate 10 billion devices connected to the internet, which form what we call the "internet of things" (IoT).



