# SD-WAN: Cisco DevNet Sandbox for SD-WAN

### Cisco SD-WAN Sandbox v1.1 
![](https://img.shields.io/badge/HandsOn-Practice-red)

This is a Cisco SD-WAN (Viptela) sandbox environment built as a collection of vagrant files and scripts to automate the deployment of the topology below. 

### Accessing the Sandbox
---
![](https://img.shields.io/badge/Secure-Tunnel-blue)

<img src="Secure VPN.png" width=200px>

``
Note: The sandbox is accessible via a secure tunnel. You will need to use the Cisco AnyConnect VPN client to establish a connection to the sandbox environment.
``



<img src="Lab Preperation.png" width=500px>



- Create a DevNet account if you don't already have one. You can sign up for free at [https://developer.cisco.com](https://developer.cisco.com).

- Reserve a sandbox at [https://devnetsandbox.cisco.com](https://devnetsandbox.cisco.com) by searching for "sd-wan" and clicking on the "Reserve" button for the "Cisco SD-WAN (Viptela) Sandbox v1.1" sandbox.



### Cisco Modeling Labs (CML2) Access & Navigation
---
![](https://img.shields.io/badge/Lab-Access-red)

Once connected to the sandbox via VPN, you can access the CML2 server at the following URL: 

[Cisco Modeling Labs](https://10.10.20.161/) 


You will be prompted to login and be able to perform the following tasks:


-  Create Network Topologies & Labs
-  Access the Lab Devices via Console
-  Model, Configure, & Test Network Topologies & Labs
-  Save & Restore Network Topologies & Labs




<img src="Navigation.gif" width=500px>



### Lab Components: SD-WAN Topology
---
![](https://img.shields.io/badge/Components-Devices-red)


- vManage:  is the centralized network management system for Cisco SD-WAN. It provides a GUI dashboard to monitor, configure, and maintain multiple vEdge routers deployed in a secure extensible network.

<p align="center">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXnqpTe9p1PDSguoTCxLaKAfgfFFysB38D-0diocfRgOsAblTXf50pmOJwUvlOHC9Kh5Y&usqp=CAU" width=50px>
</p>


- vBond: 
 is the orchestrator and single point of contact into the overlay network. It is responsible for authentication, authorization, and bringing up secure tunnels between the various components in the overlay network.

<p align="center">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJjYG69ckFLmj-su76fUHXZlJYZS0NvIZLet7zmDZymIfW20xNqssU6g3WfXB7TvhEP2k&usqp=CAU" width=50px>
</p>

- vSmart:  is the brain of the Cisco SD-WAN solution. It is responsible for building and advertising the global view of all sites to all the SD-WAN routers in the overlay network. It also runs the routing protocol between the SD-WAN routers to build the overlay network.

<p align="center">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS5Ct3ibXKjASk0256wLO4MdESjoYnNQeiesy2dv5GgCIpTgvZ01wS6MRX2Jp2nC4-hlpM&usqp=CAU" width=50px>
</p>

- vEdge Cloud:  is a virtualized version of the vEdge router that is compatible with KVM, VMware ESXi, Microsoft Hyper-V, and Oracle VirtualBox hypervisors. It is a full-featured, low-footprint, x86-based router that supports hosting of multiple virtualized network functions (VNFs) in a single platform.


<p align="center">
    <img src="computer.png" width=50px>
</p>


- DevBox (Ubuntu 16.04):  is a Linux-based virtual machine that is used to host the vManage, vBond, and vSmart controllers. It is also used to host the vEdge Cloud router.

---


### More Resources
---
![](https://img.shields.io/badge/More-Resources-red)

- [Cisco SD-WAN DevNet Learning Labs](https://developer.cisco.com/learning/modules/sd-wan)

- [Video: Cisco SD-WAN DevNet Sandbox](https://developer.cisco.com/sdwan/video/)

- [Cisco SD-WAN DevNet Sandbox](https://devnetsandbox.cisco.com/RM/Diagram/Index/0e3a3e7a-0a7a-4b0e-8b0a-8b0a8b0a8b0a)


## Author
---
<a href="http://findasnake.com">![](https://img.shields.io/badge/Authors-Used-orange)</a>

### Murtadha Marzouq
![Murtadha Marzouq](https://avatars.githubusercontent.com/u/45076915?s=200&v=4)

