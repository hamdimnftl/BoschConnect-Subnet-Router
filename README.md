# BoschConnect-Subnet-Router
Bypassed CGNAT by turning my Bosch Dishwasher into a Tailscale Subnet Router. Packets are literally squeaky clean now.
BoschConnect-Subnet-Router (BCT-Router)
Description:
A revolutionary project that turns the ESP32 Wi-Fi chip inside Bosch Home Connect Dishwashers (Series 4/6/8) into a fully functional Tailscale Subnet Router. Why buy an expensive Raspberry Pi when you have a 2400W appliance sitting idle in your kitchen? Bypassing CGNAT, one dirty plate at a time.

🌟 Enterprise-Grade Features:

Layer 7 Deep Packet Scrubbing: Operates at 70°C (158°F) to thoroughly inspect and wash incoming traffic. Removes 99.9% of malware, baked-on trackers, and stubborn viruses.

Hardware-Accelerated Cryptography: Uses physical water-softening salt (NaCl) to generate unbreakable AES-256 encryption keys. If your VPN connection is unsecure, simply add more salt to the bottom compartment.

Zero-Trust Architecture: Literally trusts zero plates. It washes everything regardless of its origin.

Advanced Load Balancing: Distributes heavy UDP traffic (pots and pans) to the bottom rack, while routing lightweight TCP packets (glasses) to the top rack for optimal throughput.

DDoS Mitigation (Distributed Dishwashing of Spoons): Automatically blocks forks from entering the spoon gateway, preventing buffer overflows in the cutlery basket.

**🛠️ Installation & Setup:**

1. SSH into your dishwasher:
```bash
ssh root@192.168.1.dishwasher
Install the required dependencies:

Bash
sudo apt-get update
sudo apt-get install calgon-network-manager finish-quantum-max
Initialize the routing table and start the wash cycle:

Bash
sudo tailscale up --advertise-routes=192.168.1.0/24 --rinse-aid=ON --eco-mode=OFF
```
⚠️ Troubleshooting & Known Issues:

High Packet Loss? Check your physical firewall (the drain filter). You probably left a piece of macaroni in the subnet gateway.

Latency is too high? You are routing traffic on "Eco Mode". Switch to "Intensive 70°" for lower ping, though it will consume more bandwidth (and water).

Kernel Panic (Error E22): Someone opened the door during a handshake protocol. Close the door firmly and run systemctl restart wash-cycle.
