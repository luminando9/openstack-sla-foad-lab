# Network Tests

## Test 1 – Internal connectivity

Instance vm-test2

IP:
192.168.222.129

Ping test result:

Successful

## Test 2 – External access using Floating IP

Floating IP:
10.20.20.218

Command executed:

ping 10.20.20.218

Result:

Reply received.

This confirms that:

- Floating IP is correctly associated
- Router performs NAT correctly
- External network access is functional

## Network topology

External Network
10.20.20.0/24

Router

Internal Network
192.168.222.0/24

Instances:

vm-test
vm-test2
