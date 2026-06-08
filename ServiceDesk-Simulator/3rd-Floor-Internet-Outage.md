# 3rd Floor Internet Outage — Network Incident

**Reported By:** Mike Reeves (mreeves@servicedesk-simulator.com)  
**Department:** Facilities  
**Location:** Floor 3  
**Contact:** x1095  
**Priority:** Critical  

---

## Problem Summary
Mike Reeves reported that the entire 3rd floor lost internet connectivity approximately 30 minutes prior. All users on that floor, including conference rooms, were unable to access any websites. Mike confirmed that the 2nd floor was unaffected, indicating the issue was isolated to the 3rd floor.

---

## Environment
- Multi‑floor office network  
- Core router in Server Room A  
- Floor‑specific switches in Server Room B  
- Wired and wireless clients  
- ServiceDesk Simulator ticketing system  

---

## Troubleshooting Steps
1. **[Opened the Server Room dashboard](ca://s?q=How_do_I_check_the_Server_Room_dashboard)** to assess network infrastructure status.  
2. Observed **two devices showing errors**:  
   - Core Router (Server Room A)  
   - Floor 3 Switch (Server Room B)  
3. Determined the outage was **localized to Floor 3**, not building‑wide, based on user report and unaffected 2nd floor.  
4. Used the Server Room tools to **reboot both the Core Router and the Floor 3 Switch**.  
5. Monitored device status as both systems came back online successfully.  
6. Contacted Mike Reeves to confirm restoration of service.  
7. Mike verified that internet connectivity was restored for all users on the 3rd floor.  
8. Marked the ticket as resolved.

---

## Root Cause
A temporary failure affecting both the **Core Router** and the **Floor 3 Switch**, resulting in a localized network outage for the entire 3rd floor.

---

## Resolution
- Rebooted the **Core Router**  
- Rebooted the **Floor 3 Switch**  
- Verified both devices returned to normal operational status  
- Confirmed with the reporting user that connectivity was fully restored  

---

## Verification
- All network devices in the Server Room dashboard show normal status  
- User confirmed full restoration of internet access  
- No additional reports of connectivity issues  

---

## What I Learned
- Floor‑wide outages often point to **switch or upstream router issues**  
- Server Room dashboards are essential for quickly identifying infrastructure failures  
- Rebooting network hardware can resolve transient faults affecting multiple devices  
- Always verify restoration with the reporting user before closing the ticket  


