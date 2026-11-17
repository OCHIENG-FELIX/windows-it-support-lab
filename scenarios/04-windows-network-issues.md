# Scenario 04: Windows Network Troubleshooting

## 1. Problem Description

A user reports that their Windows 11 computer cannot access the internet. Other computers connected to the same network appear to be working normally.

## 2. Symptoms

- No internet access.
- Browser displays connection errors.
- Applications cannot connect to online services.
- Network icon indicates limited or no connectivity.
- Network connection repeatedly disconnects.

## 3. Possible Causes

- Disabled Wi-Fi or network adapter.
- Loose or damaged Ethernet cable.
- Incorrect IP configuration.
- DHCP address assignment failure.
- Incorrect default gateway configuration.
- DNS resolution problems.
- Firewall or security restrictions.
- Router or network infrastructure issues.

## 4. Diagnostic Approach

### Step 1: Check Physical and Wireless Connections
- Confirm Wi-Fi is enabled.
- Check Ethernet cable connections.
- Verify that the computer is connected to the correct network.

### Step 2: Inspect IP Configuration

Run:

`ipconfig /all`

Review:
- IPv4 address.
- Subnet mask.
- Default gateway.
- DNS server addresses.

### Step 3: Test Network Connectivity

Run:

`ping 127.0.0.1`

This tests the local TCP/IP loopback.

Run:

`ping <default-gateway-IP>`

This tests connectivity to the configured default gateway.

Run:

`ping 8.8.8.8`

This tests connectivity to an external IP address.

### Step 4: Investigate DNS Resolution

Run:

`nslookup google.com`

Check whether the domain name resolves to an IP address.

### Step 5: Trace the Network Route

Run:

`tracert 8.8.8.8`

Review the network path and identify where responses stop, if applicable.

## 5. Recommended Resolutions

Depending on the findings:

- Reconnect to the correct Wi-Fi network.
- Secure or replace a faulty Ethernet cable.
- Enable a disabled network adapter.
- Renew the DHCP lease using approved commands.
- Investigate incorrect IP or DNS settings.
- Restart the network adapter where appropriate.
- Escalate suspected infrastructure or firewall issues to the network administrator.

## 6. Verification

- Confirm the computer has valid network configuration.
- Test connectivity to the default gateway.
- Verify external connectivity.
- Confirm DNS resolution.
- Open a website or application requiring internet access.
- Ask the user to confirm that connectivity is restored.

## 7. Preventive Recommendations

- Maintain network adapter drivers.
- Use approved network configurations.
- Inspect network cables and equipment.
- Document recurring connectivity incidents.
- Escalate infrastructure-related problems appropriately.

## 8. Current Status

**Documentation status:** Prepared.

**Practical testing status:** Pending.

**Actual root cause:** Not yet established.

**Actual resolution:** Pending practical investigation.

## Skills Demonstrated

- TCP/IP fundamentals.
- IP configuration analysis.
- DNS troubleshooting.
- DHCP fundamentals.
- Network connectivity testing.
- Command Prompt diagnostics.
- Incident documentation.
