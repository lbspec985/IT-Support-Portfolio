# Office Printer Outage — Dorothy Martinez

**Reported By:** Dorothy Martinez  
**Department:** Office Staff  
**Priority:** Medium  

---

## Problem Summary
Multiple users reported that none of the office printers were working. Print jobs were not leaving the queue, and users were unable to print any documents. This occurred during normal business hours and impacted productivity across the office.

---

## Environment
- Networked office printers  
- Central print server  
- Windows domain environment  
- ServiceDesk Simulator ticketing system  

---

## Troubleshooting Steps
- Reviewed the ticket and confirmed multiple users were affected.  
- Checked printer status through the print server dashboard.  
- Observed that printers were previously offline but had since come back online.  
- Identified that earlier in the day, a **server reboot performed during another ticket** restored connectivity to the print services.  
- Verified that all printers were now reachable and accepting jobs.  
- Tested printing from a workstation to confirm functionality.

---

## Root Cause
A required server reboot (performed while resolving a separate issue) restored the print services. The printer outage was caused by a **server-side issue**, not the printers themselves.

---

## Resolution
- Confirmed printers were back online after the server reboot  
- Tested printing from multiple workstations  
- Verified print queues were processing normally  
- Notified user that printing functionality had been restored  

---

## Verification
- Successful test prints  
- No further reports of printing issues  
- All printers showing online and operational  

---

##  What I Learned
- Printer outages can be caused by **server dependencies**, not just printer hardware  
- A fix applied during one ticket can resolve issues in another  
- Always verify system-wide services after major changes like server reboots  

