# LAB3 Inter-Subnet Routing with 4 Hosts across 2 Subnets

This lab expands on foundational networking concepts by having you build and configure a small routed network consisting of:
- 4 hosts
- 2 distinct subnets
- 1 router (Layer 3 device) connecting them

You will demonstrate practical knowledge of:
- IP addressing
- Subnet masking
- Host‑level network configuration
- Router interface setup
- Gateway configuration
- Cross‑subnet communication using a routed topology

## Containerlab topology file

LAB3EricClark.clab.yml

Starting the Lab using Containerlab terminal
-Run:
```bash
sudo containerlab deploy -t LAB3EricClark.clab.yml
```
Check nodes:
```bash
containerlab inspect -t LAB3EricClark.clab.yml
```
Access a host:
```bash
docker exec -it LAB3EricClark.clab.yml sh
```
Stopping the Lab
```bash
sudo containerlab destroy -t LAB3EricClark.clab.yml
```
