# Computer Network Project

## **The Project is based on the following specifications given below**
___
*Clone the repo and download the packet tracer file with .pkt extension for your use*
___

* Image of Network Topology
![Network Topology](https://github.com/JoyKrishan/Undergraduate-Projects/blob/master/Computer%20Networks%20Project/Packet.JPG)




## Specifications
___
BRACU has the following major schools and institutes with the mentioned characteristics 

●	SECS
○	2 departments, CSE and EEE
○	Largest school
○	16 labs (700 pc) [14 normal, 2 research lab]
○	90 faculty members and stuffs
○	More than 800 ip is needed. First 600 will be for students, rest for faculty members, staff and research purposes
○	Connects through the internet.
○	Have a local server of Youtube.com and usis.bracu.ac.bd
○	Can afford only 3 real IP

●	BBS
○	2nd largest
○	3 labs for students
○	50 faculty members and stuffs
○	Total 300 IPs needed, but they can afford only 20 real IPs

●	School of Law
○	They are strict
○	Only 14 faculty members and they do not want their ip address to be changed randomly

●	James P. Grant School of Public Health
○	Research based school
○	Their ips also need to be fixed for research purpose
○	20 pc needed

●	BIL
○	70 faculty members and stuffs
○	Listening  lab with 15 pc for students



Outside the BRACU
:
●	Assume that this is the outside network for the BRACU that they use to connect to the internet.
●	Has a single web server (browseable)

Common rules
❏	Student cannot access youtube’s local server
❏	Faculty members and staff can access youtube.com 
❏	Students of research labs can access youtube.com
❏	James P. Grant School of public health does not allow other schools to connect with their network.
❏	SECS and BIL can connect with each other, but the rest cannot access BIL.

Overall Specifications:
●	Use Routers and Switches where appropriate.
●	You may need to apply VLSM more than once
●	Packets from any other place/network is automatically denied. 
●	Install at least 2 PC/Laptop for each individual network.
●	SECS department should have a backup route to the internet
●	Use summarization if needed anywhere
●	Use at least one network with static routing, and for others use RIPv2.
●	You may use at max two PCs to represent all the hosts of a network (no need to put in 32 PCs if it says there are 32 people in the area.


Deliverables:
The network mentioned above should be implemented in packet tracer, with necessary devices and full configuration.
After completion you should be able to test the conditions imposed.
As hardcopies, you will have to submit the network topology diagram with proper labels and also all the configurations of all the routers that you have implemented.
