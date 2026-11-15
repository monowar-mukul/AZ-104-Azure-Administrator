# Lab 05 | Implement intersite connectivity

> **AZ-104: Microsoft Azure Administrator**  
> Conceptual architecture and service-flow reference. This page is **not a step-by-step lab instruction**.

## Overview

This reference explains the Azure services, responsibilities, and end-to-end flow behind **Implement intersite connectivity**.

## Azure Services Involved

### Azure Virtual Network

Azure Virtual Network contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Virtual network peering

Virtual network peering contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Route tables

Route tables contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### User-defined routes

User-defined routes contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Azure Network Watcher

Azure Network Watcher contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

## What We Are Trying to Achieve

Connect separate Azure virtual networks privately and validate the resulting traffic path.

## Architecture Diagram

![Lab 05 architecture placeholder](../images/lab-05/architecture.png)

> Add the final Azure service-flow image at `images/lab-05/architecture.png`.

## How the Services Work Together

The architecture separates the management plane, identity and authorization decisions, resource configuration, workload traffic, and monitoring. Each arrow in the final diagram should identify the operation or data flow rather than merely connect two boxes.

## Flow Sequence

### 01 | Create non-overlapping virtual network address spaces.

### 02 | Place workloads in their respective subnets.

### 03 | Test the unconnected state to establish a baseline.

### 04 | Configure peering in both directions.

### 05 | Azure routes traffic privately over the Microsoft backbone.

### 06 | Use Network Watcher to verify reachability and inspect routes.

## Hands-on Reference

[Open the hands-on reference](https://example.com/az-104/lab-05)

> Replace this dummy URL with the practical lab page. The hands-on page contains implementation exercises; this repository explains architecture and concepts.

## Key Takeaways

- Use the correct Azure service for the required control-plane or data-plane responsibility.
- Apply least privilege at the narrowest practical scope.
- Treat example resource names as examples, not mandatory Azure names.
- Validate dependencies, traffic direction, inherited access, monitoring, and recovery behavior.
- Keep the architecture page conceptual and place procedural steps in the hands-on reference.
