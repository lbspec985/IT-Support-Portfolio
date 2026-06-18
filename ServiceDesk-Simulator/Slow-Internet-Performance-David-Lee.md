# Slow Internet Performance — David Lee

**Reported By:** David Lee (dlee@servicedesk-simulator.com)  
**Department:** Customer Support | **Location:** Floor 3  
**Contact:** x2201  
**Priority:** Critical  

---

## Problem Summary
Multiple users across the office reported extremely slow internet performance. Websites were taking 20–30 seconds to load, internal WAN applications were lagging, and speed tests showed only **2 Mbps** instead of the normal **500 Mbps**. The issue affected the entire building and had been ongoing all morning.

This resulted in a company‑wide slowdown, making cloud services nearly unusable.

---

## Environment
- Entire office network  
- Core Router in Server Room  
- Users on both wired and wireless connections  
- ServiceDesk Simulator ticketing system  

---

## Troubleshooting Steps
- Confirmed the issue affected **all users**, indicating a building‑wide network problem rather than a workstation issue.  
- Went to the **Server Room** to inspect network infrastructure.  
- Navigated to **Devices** and opened the **Core Router**.  
- Performed a **router reboot** using the power control option.  
- Opened **Teams Chat** and asked the reporting user to retest internet speeds.  
- User confirmed speeds returned to normal after the reboot.

---

## Root Cause
The **Core Router** was in a degraded state, causing severe bandwidth reduction across the entire building. A reboot restored normal performance.

---

## Resolution
- Rebooted the Core Router  
- Verified restored network performance with the user  
- Confirmed normal speeds and functionality across the office  

---

## Verification
- User confirmed websites loading normally  
- Internal applications responsive again  
- Speed tests returned to expected performance (~500 Mbps)  
- No further reports of slowness  

---

## What I Learned
- The Core Router entered a degraded state due to routing table bloat or a process leak.
- Rebooting the router cleared stale routes and restored full throughput.

