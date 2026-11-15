# Lab 04 | Implement virtual networking

> **AZ-104: Microsoft Azure Administrator**  
> Conceptual architecture and service-flow reference. This page is **not a step-by-step lab instruction**.

## Overview

This reference explains the Azure services, responsibilities, and end-to-end flow behind **Implement virtual networking**.

## Azure Services Involved

### Azure Virtual Network

Azure Virtual Network contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Subnets

Subnets contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Network security groups

Network security groups contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Public IP addresses

Public IP addresses contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Azure DNS

Azure DNS contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

## What We Are Trying to Achieve

Build an isolated Azure network with segmented address spaces and controlled inbound and outbound traffic.

## Architecture Diagram

![Lab 04 architecture placeholder](../images/lab-04/architecture.png)

> Add the final Azure service-flow image at `images/lab-04/architecture.png`.

## How the Services Work Together

The architecture separates the management plane, identity and authorization decisions, resource configuration, workload traffic, and monitoring. Each arrow in the final diagram should identify the operation or data flow rather than merely connect two boxes.

## Flow Sequence

### 01 | A virtual network establishes the private IP address space.

### 02 | Subnets segment workloads by function or trust boundary.

### 03 | Network interfaces connect Azure resources to subnets.

### 04 | Network security group rules evaluate allowed and denied traffic.

### 05 | Public IP or DNS resources provide external reachability only where required.

### 06 | Connectivity and effective security rules are validated.

## Hands-on Reference

[Open the hands-on reference](https://example.com/az-104/lab-04)

> Replace this dummy URL with the practical lab page. The hands-on page contains implementation exercises; this repository explains architecture and concepts.

## Key Takeaways

- Use the correct Azure service for the required control-plane or data-plane responsibility.
- Apply least privilege at the narrowest practical scope.
- Treat example resource names as examples, not mandatory Azure names.
- Validate dependencies, traffic direction, inherited access, monitoring, and recovery behavior.
- Keep the architecture page conceptual and place procedural steps in the hands-on reference.
