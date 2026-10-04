# Bitcoin Mining Network Lab

This project is a Cisco Packet Tracer proof-of-concept network designed to simulate multiple Bitcoin ASIC miners communicating with a mining pool server.

## Network Design

- 5 simulated ASIC miners
- Miner LAN: `192.168.10.0/24`
- Default gateway: `192.168.10.1`
- Miner addresses begin at `192.168.10.101`
- Mining pool server: `10.10.10.10`

## Testing

Connectivity was tested from each simulated miner to the mining pool server.

All five miners successfully reached `10.10.10.10` with no packet loss after ARP resolution.

## Purpose

The goal of this lab was to practice:

- IP addressing
- Router configuration
- Network connectivity testing
- Troubleshooting
- Designing a network that could represent a real Bitcoin mining environment

## Lab File

`Bitcoin_Mining_Network_POC.pkt`

Open the file using Cisco Packet Tracer to view and test the network.
