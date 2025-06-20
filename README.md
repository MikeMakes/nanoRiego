# nanoRiego
NanoRiego is originally a demonstration and practice of product development. The product in question is a low-cost, modular and simple irrigation controller. Exhaustive info (in spanish) ![here](Manual_de_usuario_v0.1.pdf).   

<p align="middle">
  <img src="/nanoRiegoDOC/editables/resources/nanoRiegoPIO_clean.png" width="32%" title="nanoRiegoPCB" alt="nanoRiegoPCB">
  <img src="/nanoRiegoDOC/editables/resources/esquemaUnifilar.png" width="50%" title="Unifilar scheme" alt="Unifilar scheme">
</p>


Conceptually, the system can be divided into three elements;
* NanoRiegoPCB: Hardware Controller Device to which valves and motor are connected 
* NanoRiegoPIO: Software that runs on the controller 
* NanoRiegoAPP: User Interface, Android application to manage the system

<p align="middle">
  <img src="/nanoRiegoDOC/editables/resources/gui1.jpg" width="32%" title="Main GUI page" alt="Main GUI page">
  <img src="/nanoRiegoDOC/editables/resources/gui2.jpg" width="32%" title="GUI settings page" alt="GUI settings page">
</p>

# Capabilities
* Maintenance: Hardware components easily replaceable
* Cost: Economical hardware components
* Valves: Three (3) valve control
* Pump control: One (1) hydraulic pump control
* Manual control: Manual control of irrigation zones
* Programming: Schedule a watering cycle at a certain time, with determined duration for each zone, for certain weekdays
* Real Time: Real Time Clock with Auto Synchronization
* Persistence: Controller parameters remain without power
* Mobile interface: The user governs the controller from an Android APP
* Bluetooth: Interface and controller communicate via Bluetooth
* Automatic connection: After first connection reconnection is automatic

# To get this repo:  
> git clone --recurse-submodules https://github.com/MikeMakes/nanoRiego.git
