# IPv4-Addressess
Cisco Packet Tracer lab focused on IPv4 addressing, subnet masks, subnetting, address assignment, and network connectivity verification.


# IPv4 Addressing

## 📖 Overview

This lab focused on understanding and configuring IPv4 addresses within a Cisco network environment.

The lab provided hands-on practice with IPv4 addressing, subnet masks, network and host identification, address assignment, and connectivity testing between network devices.

## 🎯 Objectives

The lab was designed to:

* Understand the structure of an IPv4 address.
* Identify network and host portions of an address.
* Determine appropriate subnet masks.
* Configure IPv4 addresses on network interfaces.
* Assign IPv4 addresses to end devices.
* Configure default gateways.
* Verify addressing and interface configurations.
* Test connectivity between devices.
* Troubleshoot common IPv4 addressing issues.

## 🧠 Concepts Practiced

* IPv4 addressing
* Binary representation of IPv4 addresses
* Network addresses
* Host addresses
* Broadcast addresses
* Subnet masks
* CIDR notation
* Subnetting
* Default gateways
* Private IPv4 addressing
* Address assignment
* Connectivity testing

## 🛠️ Tools Used

* Cisco Packet Tracer
* Cisco IOS CLI

## ⚙️ Configuration

IPv4 addresses and subnet masks were assigned to the appropriate router interfaces and end devices according to the network topology.

Default gateways were configured on end devices to allow them to communicate with devices outside their local subnet.

Router interfaces were enabled and verified to ensure that the configured addressing was operational.

## 🧮 Addressing & Subnetting

The lab involved determining how IPv4 addresses are divided into network and host portions using subnet masks.

Subnetting allows a larger network to be divided into smaller logical networks, helping administrators efficiently manage IP address space and organize network segments.

## 🧪 Verification & Testing

IPv4 configuration was verified using commands such as:

```text
show ip interface brief
show interfaces
show running-config
```

Connectivity was tested using:

```text
ping <destination-ip>
```

These tests helped confirm that devices were correctly addressed and could communicate with their intended network destinations.

## 🔍 Troubleshooting

Common IPv4 addressing issues investigated during the lab included:

* Incorrect IP addresses.
* Incorrect subnet masks.
* Duplicate IP addresses.
* Incorrect default gateways.
* Interfaces being administratively down.
* Devices being placed in different subnets unintentionally.
* Incorrect network addressing.

Troubleshooting involved checking interface configurations, verifying addressing information, and using ping tests to identify connectivity problems.

## 🔐 Why IPv4 Addressing Matters

IPv4 addressing is one of the fundamental concepts behind computer networking.

Every device communicating over an IPv4 network requires appropriate addressing information to determine where traffic originates and where it should be delivered.

A strong understanding of IPv4 addressing and subnetting is essential for configuring routers, switches, VLANs, routing protocols, ACLs, and other network technologies.

## ✅ Outcome

Successfully configured and verified IPv4 addressing across network devices, applied appropriate subnet masks and default gateways, and tested connectivity between network segments.

## 📚 Skills Demonstrated

* Cisco IOS CLI
* IPv4 addressing
* Subnetting
* CIDR notation
* Subnet mask calculation
* Network and host identification
* Default gateway configuration
* Interface configuration
* Connectivity testing
* IPv4 troubleshooting
