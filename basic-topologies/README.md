# 📂 Basic Topologies

This folder contains Cisco Packet Tracer representations of fundamental network topologies. Each topology demonstrates a different arrangement of devices to help understand network design principles.

## 📁 Topologies Included

---

### 🌟 1. Star Topology

**File:** `star-topology.png`  

<img src="https://github.com/Ga5000/Network-Topologies-Lab/blob/main/basic-topologies/star/star-topology.png" width="400">

**Description:**  
A central switch connects to all the end devices (PCs and router). This design ensures that each device has a dedicated communication line to the switch.

**Characteristics:**
- Easy to manage and expand.
- Failure in one link doesn’t affect others.
- Central switch is a single point of failure.

---

### 🌲 2. Tree Topology

**File:** `tree-topology.png`  

<img src="https://github.com/Ga5000/Network-Topologies-Lab/blob/main/basic-topologies/tree/tree-topology.png" width="400">

**Description:**  
A hierarchical layout combining characteristics of both star and bus topologies. The main switch connects to other switches, which in turn connect to PCs.

**Characteristics:**
- Scalable structure.
- Suitable for large networks.
- Easy fault detection and isolation.

---

### 🔄 3. Hybrid (Dual Star) Topology

**File:** `hybrid-star-star-topology.png`  

<img src="https://github.com/Ga5000/Network-Topologies-Lab/blob/main/basic-topologies/hybrid/hybrid-star-star-topology.png" width="400">


**Description:**  
A hybrid topology combining two separate star topologies. Each star connects to a core switch which is then connected to a central router.

**Characteristics:**
- Inherits advantages of star topology.
- Provides redundancy and better performance.
- More complex than basic star.

---

### 🔁 4. Point-to-Point Topology

**File:** `point-to-point-topology.png`  

<img src="https://github.com/Ga5000/Network-Topologies-Lab/blob/main/basic-topologies/point-to-point/point-to-point-topology.png" width="400">

**Description:**  
A direct connection between two routers, each serving a small network. Typically used for WAN links or dedicated communication between two locations.

**Characteristics:**
- Simple and fast communication.
- Limited scalability.
- Ideal for direct device-to-device links.

---

## 📌 Notes

- These topologies are designed using **Cisco Packet Tracer**.
- You can use these templates as starting points for labs, simulations, or classroom exercises.
