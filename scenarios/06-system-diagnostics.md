# Scenario 06: Windows System Diagnostics and Performance Monitoring

## 1. Scenario Overview

**Objective:** Investigate Windows system performance using System Information and Task Manager.

Practical testing was performed on an HP EliteBook 845 G7 running Windows 11 Pro.

## 2. System Information

Used `msinfo32` to inspect the computer configuration.

| Property | Result |
|---|---|
| Operating System | Windows 11 Pro |
| OS Build | 22631 |
| Manufacturer | HP |
| Model | HP EliteBook 845 G7 Notebook PC |
| Processor | AMD Ryzen 5 PRO 4560U |
| Processor Speed | 2.10 GHz |
| CPU Cores | 6 |
| Graphics | AMD Radeon Graphics |
| Installed RAM | 8 GB |

## 3. Memory Diagnostics

Initial memory observations:

| Metric | Initial Result |
|---|---:|
| Installed RAM | 8 GB |
| Available Physical Memory | 1.13 GB |
| Available Virtual Memory | 6.21 GB |
| Total Virtual Memory | 17.3 GB |
| Committed Memory | 11.7 / 17.3 GB |

## 4. Process Investigation

Used Task Manager to identify processes consuming the most memory.

Initial observations:

| Process | Memory Usage |
|---|---:|
| Google Chrome | 3362.4 MB |
| index.html | 293.4 MB |
| Microsoft Defender | 109.0 MB |

Further investigation using Chrome Task Manager identified:

| Chrome Process | Memory Usage |
|---|---:|
| Portfolio guidance plan | 926588 KB |
| windows-it-support-lab/scenarios | 368296 KB |
| Felix Otieno Ochieng' / IT Support | 203104 KB |

Six Chrome tabs were initially open.

## 5. Troubleshooting Action

After confirming that three tabs were no longer required, they were closed.

No critical processes were terminated, and Microsoft Defender was not disabled.

## 6. Before-and-After Results

| Metric | Before | After |
|---|---:|---:|
| Available Memory | 1.13 GB | 1.9 GB |
| Committed Memory | 11.7 GB | 9.8 GB |
| Installed RAM | 8 GB | 8 GB |

Available physical memory increased by approximately 770 MB.

Committed memory decreased by approximately 1.9 GB.

## 7. User Experience Verification

After closing unnecessary browser tabs, the user reported improved computer responsiveness when switching between applications, opening folders, and browsing websites.

## 8. Conclusion

The investigation identified Google Chrome as the largest memory-consuming application.

Closing unnecessary browser tabs reduced memory pressure and improved system responsiveness.

The exercise demonstrated the importance of investigating resource usage, identifying the underlying cause, obtaining user confirmation before changes, and verifying results after taking corrective action.

## 9. Skills Practised

- Windows System Information (`msinfo32`).
- Task Manager performance monitoring.
- Physical and virtual memory interpretation.
- Process-level memory investigation.
- Chrome Task Manager.
- Performance troubleshooting.
- Before-and-after verification.
- Technical documentation.
