<h1>Analyzing Databases</h1>
<h2>Description</h2>
IP Networking: Communication between different networks is facilitated by internet protocol. In this instance, Project 
Two consists of Subnets 1 and 2 and Network 3. To accomplish the necessary work to establish 
connections between PC1 in Subnet 1 and PC1 in Subnet 2 and connect to Server Main, I had first to 
establish the necessary paths that would allow these two subsystems to talk to one another. I had to create 
static and dynamic routes at the Server Router in Subnet 2 to do this. I chose to make both routes because 
static routes can be somewhat unreliable. 

Subnet Masks: A network is divided into smaller networks with the help of subnet masks. Take Subnet1 and Subnet2, for 
example. They are components of the same large network but utilize different addressing schemes. 
Subnet1 has the address 192.168.1.1, while Subnet2 operates under 192.168.5.1. This kind of setup can 
enhance security and be a better way of managing network traffic. 

Network (DHCP) infrastructure: This project could have been designed using DHCP infrastructure, but I instead used static routes and RIP  
to focus my understanding of those protocols. 

Network address translation (NAT) protocol and port address translation (PAT) protocol: Use the NAT and PAT protocols at the CLI or GUI to designate which port on the router is inside or outside, enabling the end-to-end devices to interact. For example, the server router has two ports, Fa0/0 and Se2/0. In this case, port Fa0/0 was connected to server main outside the server router, and port Se2/0 was set up inside the server router to connect to subnet router. 

For my project, I have been assigned as a “Junior Security Analyst,” and my task for this project is to integrate Subnet1 and Subnet2 into “Network A.” I configured both the static routing for both networks and Network 3. I configured DNS, DHCP, and NAT services. I pinged to check the communications between the two networks. I moved all the equipment from Subnet2 to Subnet1, including PCs and printers. For the new 192.168.1.1 gateway to replace the previous gateway, I reconfigured the gateway and assigned it a static IP address. Next, I used a serial cable to join the Subnet Router and the Network3 Router. Remember that, compared to fast ethernet connections, fiber connections, or simply faster methods to move packets around, this network won't perform as well. I implemented RIP, set up static routing between the two routers, and validated that both networks can interact. The Network 3 Server was configured so DHCP and DNS could operate. This limited the number of users that could log on to the network and assigned a logical IP address to those identified by the network. I then ran a PDU command to ping from a PC on Network 3 to a PC on Network A and viewed that output. Next, I executed the successful ping command from a PC on Network 3 to a PC on Network A. Then, just to ensure all was in order, I commanded a ping from a PC on Network "A" to a PC on "Network 3."

<h2>Environments Used </h2>
- <b>Cisco Packet Tracer</b>

<h2>Program walk-through:</h2>
<p align="center"> <br/>
<img src="https://i.imgur.com/7y9zM0s.png"/>
<img src="https://i.imgur.com/e6XIw4p.png"/>
<img src="https://i.imgur.com/A4uOxyl.png"/>
<img src="https://i.imgur.com/SiNhrZD.png"/>
<img src="https://i.imgur.com/q9n4jOn.png"/>
<img src="https://i.imgur.com/yFpGfSi.png"/>
