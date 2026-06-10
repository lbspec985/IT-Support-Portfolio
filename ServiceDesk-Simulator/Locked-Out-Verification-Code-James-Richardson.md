# Locked Out – Verification Code Not Working (James Richardson)

**Reported By:** James Richardson (jrichardson@servicedesk-simulator.com)  
**Department:** Executive | **Location:** Floor 1  
**Contact:** x1001  
**Priority:** High  

---

## Problem Summary
James Richardson reported that he was unable to log in due to a verification code prompt that was not sending codes to his phone. He stated that the MFA process worked the previous day but no longer sends any messages. He attempted multiple login attempts and restarted his phone, but the verification code still did not arrive.

This prevented him from accessing all company systems on a day with a critical project deadline.

---

## Environment
- Windows workstation  
- MFA-enabled corporate account  
- Executive department  
- ServiceDesk Simulator ticketing system  

---

##  Troubleshooting Steps
- Connected to the user’s workstation through **Remote Support**.  
- Observed that the workstation was **not connected to the corporate VPN**, which can prevent MFA services from communicating properly.  
- Connected the workstation to the **corporate VPN**.  
- Opened **Active Directory → User → Authentication**.  
- Selected **Reset MFA** to clear the user’s existing authentication configuration.  
- Instructed the user to attempt login again.  
- User successfully received a new verification code and authenticated without issues.

---

## Root Cause
The user’s workstation was not connected to the **corporate VPN**, preventing MFA services from syncing properly. Resetting MFA re-established the authentication configuration once VPN connectivity was restored.

---

## Resolution
- Connected user to corporate VPN  
- Reset MFA settings in Active Directory  
- User successfully received verification code  
- Login restored and user regained access to all systems  

---

## Verification
- User confirmed successful login  
- MFA codes now sending normally  
- No further issues reported  

---

##  What I Learned
- MFA failures can occur when a workstation is not connected to the corporate VPN  
- Resetting MFA in AD is an effective fix when verification codes stop sending  
- Always check network connectivity before troubleshooting authentication issues  

