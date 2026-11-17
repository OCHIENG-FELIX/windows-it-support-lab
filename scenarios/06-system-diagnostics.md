# Scenario 06: Windows System Diagnostics

## 1. Problem Description

A user reports that their Windows 11 computer experiences unexpected restarts, application crashes, and occasional system errors.

The issue appears intermittently, making it necessary to investigate system health and identify possible causes.

## 2. Symptoms

- Unexpected computer restarts.
- Applications crashing unexpectedly.
- Windows error notifications.
- System freezing.
- Unusual system behaviour.
- Occasional startup problems.

## 3. Possible Causes

- Corrupted Windows system files.
- Outdated or incompatible device drivers.
- Hardware problems.
- Software conflicts.
- Failed Windows updates.
- Storage-related issues.
- Overheating or power-related problems.

## 4. Diagnostic Approach

### Step 1: Review System Information

Run:

`msinfo32`

Inspect:
- Operating system information.
- Installed memory.
- Hardware configuration.
- System components.

### Step 2: Review Windows Event Logs

Run:

`eventvwr.msc`

Inspect:
- System logs.
- Application logs.
- Critical events.
- Error events.
- Events occurring around the reported failure time.

### Step 3: Check System File Integrity

Open Command Prompt as Administrator and run:

`sfc /scannow`

This checks protected Windows system files and attempts repairs where possible.

### Step 4: Investigate Storage

Run:

`diskmgmt.msc`

Inspect:
- Disk configuration.
- Partition status.
- Available storage space.

Use appropriate storage health diagnostics when hardware problems are suspected.

### Step 5: Investigate Recent Changes

Review:
- Recently installed applications.
- Recent Windows updates.
- Driver updates.
- Changes to system configuration.

## 5. Recommended Resolutions

Depending on the findings:

- Repair corrupted system files.
- Install approved Windows updates.
- Update or roll back problematic device drivers.
- Remove conflicting software through approved procedures.
- Investigate suspected hardware failures.
- Escalate serious or recurring system failures to Level 2 support or the appropriate specialist.

## 6. Verification

- Restart the computer where required.
- Confirm that Windows starts successfully.
- Test applications previously experiencing errors.
- Review new Event Viewer entries.
- Monitor the system for recurring failures.
- Confirm with the user that normal operation has resumed.

## 7. Preventive Recommendations

- Maintain regular backups.
- Keep Windows and drivers appropriately updated.
- Install trusted software only.
- Monitor system health.
- Document recurring system errors.
- Follow organizational maintenance and security policies.

## 8. Current Status

**Documentation status:** Prepared.

**Practical testing status:** Pending.

**Actual root cause:** Not yet established.

**Actual resolution:** Pending practical investigation.

## Skills Demonstrated

- Windows system diagnostics.
- Event Viewer analysis.
- System file integrity checking.
- Hardware and software investigation.
- Windows maintenance.
- Technical documentation and escalation.
