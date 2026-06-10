# Second Monitor Issue — Amanda Foster

**Reported By:** Amanda Foster (afoster@servicedesk-simulator.com)  
**Department:** Finance | **Location:** Floor 2  
**Contact:** x4110  
**Priority:** Medium  

---

## Problem Summary
Amanda Foster reported that her second monitor was displaying a **“No Signal”** message. The monitor powered on, but her workstation did not detect it. The issue began today, despite the monitor working normally the previous day. Amanda attempted several troubleshooting steps on her own, including checking cables, swapping cables, testing alternate ports, restarting her PC, and testing the monitor with a coworker’s laptop — where it worked successfully. This confirmed the monitor itself was functional.

The issue reduced her productivity during **month‑end close**, where dual monitors are essential for financial reporting.

---

## Environment
- Windows workstation  
- Dual‑monitor setup  
- Finance department  
- ServiceDesk Simulator ticketing system  

---

## Troubleshooting Steps
- Connected to the user’s workstation through **Remote Support**.  
- Navigated to **Settings** to locate display configuration options.  
- Noticed a **pending Windows system update** under System Update.  
- Determined that outdated system components or display drivers could be preventing the second monitor from being detected.  
- Installed the available Windows update.  
- After the update completed and the workstation restarted, the second monitor was automatically detected and functioning normally.  

---

## Root Cause
The workstation required a **Windows update**, which included system and driver updates necessary for proper multi‑monitor detection. The outdated system state prevented the second monitor from being recognized.

---

## Resolution
- Connected via Remote Support  
- Identified pending Windows update  
- Installed update and rebooted workstation  
- Verified that the second monitor was detected and functioning  
- User confirmed full dual‑monitor functionality restored  

---

## Verification
- User confirmed both monitors working  
- No further issues reported  
- Productivity restored during month‑end close  

---

## What I Learned
- A “No Signal” message can be caused by **software or driver issues**, not just hardware  
- Windows updates often include display driver fixes that resolve detection problems  
- User‑performed troubleshooting can help narrow down the issue quickly  
- Remote Support is essential for confirming system state and identifying update requirements  

