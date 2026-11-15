# Lab 11 | Implement monitoring

> **AZ-104: Microsoft Azure Administrator**  
> Conceptual architecture and service-flow reference. This page is **not a step-by-step lab instruction**.

## Overview

This reference explains the Azure services, responsibilities, and end-to-end flow behind **Implement monitoring**.

## Azure Services Involved

### Azure Monitor

Azure Monitor contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Log Analytics workspace

Log Analytics workspace contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Azure Monitor Agent

Azure Monitor Agent contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Activity Log alerts

Activity Log alerts contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Action groups

Action groups contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

### Alert processing rules

Alert processing rules contributes a specific capability to this architecture. Its configuration should be validated against the required scope, security boundary, and operational outcome.

## What We Are Trying to Achieve

Collect platform and guest signals, query telemetry, and notify operators when important administrative events occur.

## Architecture Diagram

![Lab 11 architecture placeholder](../images/lab-11/architecture.png)

> Add the final Azure service-flow image at `images/lab-11/architecture.png`.

## How the Services Work Together

The architecture separates the management plane, identity and authorization decisions, resource configuration, workload traffic, and monitoring. Each arrow in the final diagram should identify the operation or data flow rather than merely connect two boxes.

## Flow Sequence

### 01 | Azure Monitor Agent sends configured guest data to Log Analytics.

### 02 | Platform operations are recorded in the Azure Activity Log.

### 03 | KQL queries analyse heartbeat, performance, and collected events.

### 04 | An alert rule evaluates a signal such as virtual-machine deletion.

### 05 | An action group sends the configured notification.

### 06 | An alert processing rule can suppress notifications during maintenance.

## Hands-on Reference

[Open the hands-on reference](https://example.com/az-104/lab-11)

> Replace this dummy URL with the practical lab page. The hands-on page contains implementation exercises; this repository explains architecture and concepts.

## Key Takeaways

- Use the correct Azure service for the required control-plane or data-plane responsibility.
- Apply least privilege at the narrowest practical scope.
- Treat example resource names as examples, not mandatory Azure names.
- Validate dependencies, traffic direction, inherited access, monitoring, and recovery behavior.
- Keep the architecture page conceptual and place procedural steps in the hands-on reference.
