# Google IT Support Certificate — Learning Journal

Progress tracker and key concepts from the Google IT Support
Certificate on Coursera.

---

## Course 1 — Technical Support Fundamentals ✅
**Completed:** June 2026
**Certificate:** [Verify here](https://coursera.org/verify/7JMRB1IAVQY8)

### Key Concepts Learned

**Binary & Data**
- 1 byte = 8 bits, each bit is either a 0 or 1
- To convert decimal to binary: divide by powers of 2 from left to right
- Character encoding (UTF-8, ASCII) assigns characters to binary values

**Hardware**
- CPU processes all calculations — uses MCC to find data in RAM
  and EDB to transfer it to the CPU
- RAM is short-term memory — data is lost when powered off
- HDD vs SSD: SSD has no moving parts — faster and more durable
- POST runs at startup to verify all hardware is working correctly
- BIOS initializes hardware and loads drivers — settings stored in CMOS
- Northbridge — handles fast communication (CPU, RAM, video card)
- Southbridge — handles slower devices (USB, audio, storage)
- ATX is the most common motherboard form factor
- LGA and PGA are the two most common CPU socket types

**Operating Systems**
- OS has two main parts: Kernel (communicates with hardware)
  and Userspace (where applications run)
- Boot process: BIOS → POST → Bootloader → Kernel → Userspace
- System software keeps the core OS running
- Application software is what users interact with directly
- File management components: File system, File data, Metadata
- NTFS is the most common file system in Windows

**Software & Linux Basics**
- `sudo apt-get update` — updates the package repository
- `sudo apt-get install [package]` — installs a software package
- `dpkg -s [package]` — checks if a package is installed
- `sudo apt-get remove [package]` — uninstalls a package
- Git tracks changes to files and directories
- Scripting automates repetitive IT tasks like updates and backups

**Troubleshooting Methodology**
1. Gather information — never assume the problem
2. Establish a theory of probable cause
3. Test the theory
4. Create an action plan
5. Implement the solution
6. Verify full functionality
7. Document everything

- Always start with the fastest and simplest solution
- Goal is always to identify the root cause, not just the symptom
- Use ticketing systems to track, communicate and follow up
- Acknowledge the user first — empathy is key in IT support

---

## Course 2 — The Bits and Bytes of Computer Networking 🔄
**Status:** In progress

### Key Concepts Learned So Far

**TCP/IP 5-Layer Model**
| Layer | Name | Examples |
|-------|------|---------|
| 5 | Application | Browser, HTTP, DNS |
| 4 | Transport | TCP, UDP |
| 3 | Network | IP, Routers |
| 2 | Data Link | Ethernet, Switch, WiFi |
| 1 | Physical | Cables, connectors |

**Network Devices**
- **Hub** — Layer 1, sends data to all devices, no inspection,
  causes collision domains. Obsolete.
- **Switch** — Layer 2, inspects MAC addresses, sends data only
  to the correct device. Standard in modern networks.
- **Router** — Layer 3, forwards traffic between independent networks.
  Uses routing tables and IP addresses.
- **Modem** — converts digital signals for ISP transmission
- **Access Point** — extends LAN wirelessly (WiFi)
- **Server** — provides data to clients (email, files, web)
- **Client** — requests data from servers

**Cables**
- Copper (Cat5, Cat5e, Cat6) — voltage changes represent binary data
- Fiber optic — pulses of light, faster and interference-resistant
- Twisted pair cables reduce crosstalk (electromagnetic interference)
- Three types of twisted pair: UTP, STP, FTP
- Cat5e → up to 1 Gbps | Cat6 → up to 10 Gbps

**Duplexing**
- Full duplex — both directions simultaneously (modern switches)
- Half duplex — one direction at a time (degraded connections)
- Simplex — one direction only, no response (TV broadcast, radio)

**Physical Layer**
- Line coding converts digital data (1s and 0s) into transmittable signals
- Port lights on switches provide instant troubleshooting data
- Physical layer abstracts hardware details from all other layers

**Data Link Layer**
- Ethernet - protocol that allows devices to communicate within a local area network
- MAC Address, is a globally unique identifier assigned to a network interface
- Octet, is any value that can be represented using 8 bits.
- CSMA/CD (Carrier Sense Multiple Access with Collision Detection), If two devices transmit data at the same time and a collision occurs,
each device waits for a random amount of time before attempting to retransmit.

**Types of Ethernet transmission**
- unicast - Data is transmitted to a single device
- multicast - data is transmitted to a different devices, but only devices that have agreed to receive the data will process it.
- Broadcast - the message is sent to all devices connecteted to the network, every devices receives it.




*(keep adding concepts as you progress through each module)*

---

## Course 3 — Operating Systems and You ⏳
**Status:** Pending

---

## Course 4 — System Administration and IT Infrastructure ⏳
**Status:** Pending

---

## Course 5 — IT Security: Defense against the Digital Arts ⏳
**Status:** Pending
