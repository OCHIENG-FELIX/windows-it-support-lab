# Scenario 05: Windows Device Manager and Driver Troubleshooting

## 1. Scenario Overview

**Objective:** Inspect Windows hardware devices, identify potential driver issues, and assess device status using Device Manager.

This practical exercise was performed on a new Windows 11 computer.

## 2. Practical Investigation

### Step 1: Open Device Manager

Opened Device Manager using the Windows + X shortcut.

Inspected the available hardware categories for:
- Yellow warning symbols.
- Disabled devices.
- Unknown devices.

**Observation:** No warning symbols, disabled-device indicators, or unknown devices were identified.

### Step 2: Inspect Network Adapter

Expanded Network adapters and opened the properties of the wireless network adapter.

**Device identified:**

Intel(R) Wi-Fi 6 AX200 160MHz

### Step 3: Inspect Device Status

Checked the General tab under the adapter's Properties.

**Result:** Windows reported:

`This device is working properly.`

### Step 4: Inspect Driver Information

Opened the Driver tab and recorded:

| Property | Observation |
|---|---|
| Driver Provider | Intel |
| Driver Version | 23.120.0.3 |
| Device Status | Working properly |

No driver updates or modifications were performed.

## 3. Troubleshooting Knowledge Applied

Considered a simulated scenario in which a user experiences frequent Wi-Fi disconnections despite Device Manager reporting that the adapter is functioning properly.

Identified the appropriate next investigations:

1. Check wireless signal strength.
2. Determine whether other devices experience the same problem.
3. Check connectivity to the default gateway.
4. Investigate possible wireless interference.
5. Examine router or access-point connectivity.

**Decision:** Investigate network conditions before attempting driver reinstallation or hardware replacement.

## 4. Key Findings

- Device Manager showed no visible hardware or driver warnings.
- The Intel Wi-Fi adapter was detected successfully.
- Windows reported that the adapter was functioning properly.
- Driver information was successfully identified.
- No unnecessary driver modifications were made.

## 5. Skills Practised

- Windows Device Manager navigation.
- Hardware identification.
- Driver information inspection.
- Basic driver fault assessment.
- Network adapter troubleshooting.
- Evidence-based troubleshooting decisions.

## 6. Practical Outcome

**Status:** Practical inspection completed.

The exercise confirmed that the network adapter had no visible Device Manager errors. It did not establish that all possible wireless connectivity problems were absent.
