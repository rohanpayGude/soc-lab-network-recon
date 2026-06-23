# VM Networking Configuration

## Network Type

The lab uses:

- VirtualBox Host-only Adapter

This creates an isolated virtual network between the Analyst VM and Target VM.

## Lab Network

Analyst VM:
- IP Address: 192.168.56.102

Target VM:
- IP Address: 192.168.56.101

## Network Troubleshooting

During setup, the Analyst VM was initially configured with Bridged networking.

This caused communication issues because the Analyst VM and Target VM were placed on different networks.

The issue was resolved by moving both machines to the same Host-only network.

## Result

Both virtual machines were able to communicate successfully.
