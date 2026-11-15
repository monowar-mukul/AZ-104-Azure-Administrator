# Lab 08 | Manage virtual machines

> **AZ-104: Microsoft Azure Administrator**  
> Conceptual architecture and service-flow reference. This page is **not a step-by-step lab instruction**.

## Overview

This reference explains the Azure services, responsibilities, and end-to-end flow behind **Manage virtual machines**.

## Azure Services Involved

### Azure Virtual Machines

Azure Virtual Machines contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Managed disks

Managed disks contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Availability Zones

Availability Zones contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Virtual Machine Scale Sets

Virtual Machine Scale Sets contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Azure Monitor

Azure Monitor contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

## What We Are Trying to Achieve

Operate individual virtual machines and automatically scaled groups while maintaining availability, storage, and observability.

## Architecture Diagram

![Lab 08 architecture placeholder](../images/lab-08/architecture.png)

> Add the final Azure service-flow image at `images/lab-08/architecture.png`.

## How the Services Work Together

The architecture separates the management plane, identity and authorization decisions, resource configuration, workload traffic, and monitoring. Each arrow in the final diagram should identify the operation or data flow rather than merely connect two boxes.

## Flow Sequence

### 01 | Deploy virtual machines into the required availability zones and subnet.

### 02 | Managed OS and data disks provide persistent storage.

### 03 | Resize a deallocated VM when workload capacity changes.

### 04 | Deploy a scale set for a uniform pool of VM instances.

### 05 | Azure Monitor metrics drive scale-out and scale-in rules.

### 06 | Validate instance health, capacity, networking, and disk state.

## Hands-on Reference

[Open the hands-on reference](https://example.com/az-104/lab-08)

> Replace this dummy URL with the practical lab page. The hands-on page contains implementation exercises; this repository explains architecture and concepts.

## Key Takeaways

- Use the correct Azure service for the required control-plane or data-plane responsibility.
- Apply least privilege at the narrowest practical scope.
- Treat example resource names as examples, not mandatory Azure names.
- Validate dependencies, traffic direction, inherited access, monitoring, and recovery behavior.
- Keep the architecture page conceptual and place procedural steps in the hands-on reference.
