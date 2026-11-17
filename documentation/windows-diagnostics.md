# Windows Diagnostics

## Overview

Windows provides several built-in diagnostic tools that help IT Support Technicians identify, investigate, and troubleshoot hardware, software, performance, and system-related issues.

## 1. Task Manager

**Purpose:** Monitor system resource utilization and running processes.

Key resources:
- CPU: Measures processor utilization.
- Memory: Shows RAM consumption.
- Disk: Displays storage activity.
- Network: Shows network utilization.

**Common use cases:**
- Investigating slow computer performance.
- Identifying resource-intensive applications.
- Monitoring unresponsive processes.

## 2. Device Manager

**Purpose:** Manage and inspect installed hardware devices and their drivers.

Common use cases:
- Identifying devices with driver problems.
- Checking hardware status.
- Updating or reinstalling device drivers.

## 3. Event Viewer

**Purpose:** Review Windows system and application logs.

Important log categories:
- Application
- Security
- Setup
- System

Common use cases:
- Investigating application crashes.
- Identifying system errors.
- Reviewing unexpected shutdown events.

## 4. Command Prompt

Useful diagnostic commands:

| Command | Purpose |
|---|---|
| `ipconfig` | Displays network configuration |
| `ipconfig /all` | Displays detailed network configuration |
| `ping` | Tests connectivity to a destination |
| `tracert` | Displays the route to a destination |
| `nslookup` | Investigates DNS resolution |
| `sfc /scannow` | Scans and repairs protected Windows system files |

## 5. Windows System Information

**Command:** `msinfo32`

Purpose:
- Displays hardware information.
- Shows system specifications.
- Provides information about Windows components and system configuration.

## 6. Disk Management

**Command:** `diskmgmt.msc`

Purpose:
- Inspect connected storage devices.
- View disk partitions and volumes.
- Investigate storage configuration issues.

## Conclusion

Understanding these diagnostic tools enables IT Support Technicians to gather evidence, investigate technical problems, and make informed troubleshooting decisions.
