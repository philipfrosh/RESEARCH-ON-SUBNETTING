Subnetting

## What is Subnetting?
Subnetting is the process of dividing one large IP network into smaller, manageable networks called **subnets**.  
It helps networks operate **faster, safer, and more efficiently**.

---

## Why is Subnetting Important?
Subnetting is used to:  
1. **Reduce network traffic** – Less congestion on each subnet.  
2. **Improve network security** – Limits access to specific subnets.  
3. **Use IP addresses efficiently** – Avoids wasting addresses.  
4. **Make troubleshooting easier** – Problems can be isolated to a subnet.  
5. **Organize large networks** – Makes network management simpler.

---

## Key Terms in Subnetting
- **IP Address:** Identifies a device on a network.  
  *Example:* `192.168.1.10`  
- **Network Address:** Identifies the network itself.  
  *Example:* `192.168.1.0`  
- **Broadcast Address:** Sends data to all devices in a subnet.  
  *Example:* `192.168.1.255`  
- **Subnet Mask:** Shows which part of an IP is the network and which part is the host.  
  *Example:* `255.255.255.0`

---

## Classes of IP Addresses

| Class | Range                    | Default Subnet Mask |
|-------|--------------------------|-------------------|
| A     | 1.0.0.0 – 126.0.0.0      | 255.0.0.0         |
| B     | 128.0.0.0 – 191.255.0.0  | 255.255.0.0       |
| C     | 192.0.0.0 – 223.255.255.0 | 255.255.255.0    |

> **Note:** Subnetting is mostly done in **Class C networks** for learning and practical applications.

---

## How Subnetting Works
Subnetting **borrows bits** from the host part of an IP address to create more networks.

**Example:**  
- Original subnet mask: `255.255.255.0 (/24)`  
- New subnet mask: `255.255.255.192 (/26)`  

This creates:  
- **4 subnets**  
- **62 usable hosts per subnet**

> **CIDR (Classless Inter-Domain Routing)** uses a slash (/) to show the number of network bits.  
> Example: `/24 = 255.255.255.0`

---

## Advantages of Subnetting
1. Faster communication  
2. Better network security  
3. Efficient IP address management  
4. Easier maintenance and troubleshooting  

---

## Real-Life Example
A school network may use subnets to separate:  
- Students  
- Teachers  
- Administration  

This improves **control, security, and performance** of the network.

---

## Conclusion
Subnetting is a **core networking skill** that divides networks into smaller, manageable parts. It enhances **performance, security, and management**.  
A strong understanding of subnetting is essential for **networking, cybersecurity, and system administration**.
