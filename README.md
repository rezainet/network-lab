# network-lab

Hands-on networking labs I build while preparing for Cisco CCNA (exam December 2026), and groundwork for my MSc thesis on network validation.

## Contents

- packet-tracer/: one folder per topic, each with the .pkt file, a topology diagram and the commands used to verify it
- containerlab/leaf-spine-bgp/: a 2-spine, 4-leaf BGP fabric on FRR
- python/: small netmiko scripts for config backup and VLAN provisioning

## Quick start

```bash
cd containerlab/leaf-spine-bgp && sudo containerlab deploy -t topology.clab.yml
```

The topology file is a skeleton. Working FRR configs are planned for January 2027. See the roadmap.

## Roadmap

1. CCNA labs (Sep to Dec 2026)
2. Leaf-spine fabric (Jan 2027)
3. Batfish and gNMI pipeline for my MSc thesis (2027)

## Status

Labs are added weekly as I work through the CCNA curriculum.
