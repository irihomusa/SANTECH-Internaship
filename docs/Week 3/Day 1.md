# Day 1 – Week 3

## Designing and Configuring a Multi-Department Network in Cisco Packet Tracer

### 📝 Description

On Day 1 of Week 3, we focused on designing and configuring a complete network infrastructure for a simulated company (S Ltd) using Cisco Packet Tracer. The company consisted of three departments: Administration, Sales, and IT, distributed across two floors within a single building.

The objective was to ensure efficient communication, proper network segmentation, and shared resource access across all departments.

We began by designing the physical topology, placing network devices such as routers, switches, end devices (PCs), a server, and a network printer. Each department was logically grouped and connected through switches based on their floor location.

To enhance network organization and security, Virtual Local Area Networks (VLANs) were implemented. Each department was assigned a unique VLAN:

- VLAN 10 for Administration  
- VLAN 20 for Sales  
- VLAN 30 for IT  

This allowed traffic isolation while maintaining controlled inter-department communication.

We configured trunk links between switches and the router to enable VLAN tagging and implemented Inter-VLAN routing using the Router-on-a-Stick method. This allowed devices from different VLANs to communicate through the router.

Dynamic IP addressing was configured using DHCP on the router, ensuring automatic IP assignment to all client devices. Additionally, the server was configured with a static IP address and enabled with services such as HTTP and file sharing, allowing centralized resource access.

The network printer was also configured and made accessible across all departments.

Finally, connectivity testing was performed using ping commands to verify successful communication between devices, departments, and shared resources.

---

### 🎯 Objectives Achieved

- Designed a structured enterprise network  
- Implemented VLAN segmentation  
- Configured inter-VLAN routing  
- Enabled DHCP for automatic IP assignment  
- Set up a server for file sharing  
- Configured a shared network printer  
- Verified full network connectivity  

---

### 🧰 Tools Used

- Cisco Packet Tracer  
- VLANs  
- Routing  
- DHCP  
