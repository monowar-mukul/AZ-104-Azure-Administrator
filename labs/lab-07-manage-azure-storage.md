# Lab 07 | Manage Azure Storage

> **AZ-104: Microsoft Azure Administrator**  
> Conceptual architecture and service-flow reference. This page is **not a step-by-step lab instruction**.

## Overview

This reference explains the Azure services, responsibilities, and end-to-end flow behind **Manage Azure Storage**.

## Azure Services Involved

### Azure Storage account

Azure Storage account contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Blob Storage

Blob Storage contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Azure Files

Azure Files contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Lifecycle management

Lifecycle management contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Azure RBAC

Azure RBAC contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

## What We Are Trying to Achieve

Provide durable object and file storage with controlled access, data protection, and lifecycle-based cost management.

## Architecture Diagram

![Lab 07 architecture placeholder](../images/lab-07/architecture.png)

> Add the final Azure service-flow image at `images/lab-07/architecture.png`.

## How the Services Work Together

The architecture separates the management plane, identity and authorization decisions, resource configuration, workload traffic, and monitoring. Each arrow in the final diagram should identify the operation or data flow rather than merely connect two boxes.

## Flow Sequence

### 01 | Create a general-purpose v2 storage account with the required redundancy.

### 02 | Restrict network exposure and assign data-plane access roles.

### 03 | Store objects in a private blob container.

### 04 | Apply retention, soft-delete, or immutability settings where required.

### 05 | Use lifecycle rules to move aging blobs to a cooler tier.

### 06 | Clients access blobs over HTTPS or mount Azure file shares using SMB.

## Hands-on Reference

[Open the hands-on reference](https://example.com/az-104/lab-07)

> Replace this dummy URL with the practical lab page. The hands-on page contains implementation exercises; this repository explains architecture and concepts.

## Key Takeaways

- Use the correct Azure service for the required control-plane or data-plane responsibility.
- Apply least privilege at the narrowest practical scope.
- Treat example resource names as examples, not mandatory Azure names.
- Validate dependencies, traffic direction, inherited access, monitoring, and recovery behavior.
- Keep the architecture page conceptual and place procedural steps in the hands-on reference.
