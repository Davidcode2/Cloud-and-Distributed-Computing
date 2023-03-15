---
title: Containers, Orchestration, Service Mesh
date: 2023-03-15
---

# Lab 1 

## Containers, Orchestration, Service Mesh

# Ecosystem - other containerization solutions

[source](https://www.redhat.com/en/topics/virtualization/what-is-a-hypervisor)

Docker is an alternative to hypervisor

### what is a hypervisor?

A hypervisor is the software that creates and manages virtual machines.
It is also sometimes referred to as a virtual machine monitor (VMM).
The hypervisor isolates the operating system and resources from the virtual machines.

## alternatives

### Rkt (pronounced rocket)

Rkt is a competitor from CoreOS
Rkt supports other container formats besides its own which is called ACI.
Any container can be converted to ACI using the open source tool Quay.
Rkt does not rely on a central background process (like the docker daemon)
and instead runs each container using established init systems like systemd
and upstart.

### LXC

Linux Containers are very similar to VMs but come without their overhead.
They do not need to simulate all the hardware and do not run a seperate kernel.

LXC is a linux container runtime that
consists of tools, templates, and library and language bindings
[source](https://linuxcontainers.org/)

### LXD

LXD is the next generation system container and virtual machine manager.

