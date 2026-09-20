# cisco-vlan-trunking-lab

Layer 2 VLAN Segmentation and Trunking lab built on Cisco Packet Tracer.

## 📐 Network Topology
![Topology](./1.%20Topology.png)

## 📊 Addressing & VLAN Scheme

| VLAN ID | Name | Subnet |
| :--- | :--- | :--- | :--- |
| **VLAN 10** | ID | `192.168.10.0/24` |
| **VLAN 20** | DEV | `192.168.20.0/24` |
| **VLAN 30** | TRI | `192.168.30.0/24` |

## 🛠️ Tasks Completed
1. **Topology Setup:** Connected 3 switches and 9 PCs across distinct subnets.
2. **VLAN Configuration:** Created VLANs 10, 20, and 30 across all switches.
3. **Access Configuration:** Configured host-facing switchports as access ports and assigned them to their respective VLANs.
4. **Trunking Configuration:** Configured inter-switch links (`Fa0/5`) as 802.1Q trunk ports to carry traffic across switches.
5. **Verification:** Validated VLAN tables (`show vlan brief`), trunk links (`show interfaces trunk`), and tested ICMP reachability within identical VLANs.

## 📁 Repository Files
* `cisco-vlan-trunking.pkt`: Packet Tracer source file.
* `1. Topology.png`: Topology visual representation.
* `2. VLAN Table.png`: Output of `show vlan brief`.
* `3. Trunk Interfaces.png`: Output of `show interfaces trunk`.
* `4. Exercice VLAN.pdf`: Lab instruction sheet.

## 🚀 How to Run
1. Download and install [Cisco Packet Tracer](https://www.netacad.com/).
2. Clone or download this repository.
3. Open `cisco-vlan-trunking.pkt` to inspect configurations or test ping connectivity.
