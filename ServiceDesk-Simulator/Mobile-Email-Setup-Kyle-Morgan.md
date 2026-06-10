# Mobile Email Setup — Kyle Morgan

**Reported By:** Kyle Morgan (kmorgan@servicedesk-simulator.com)  
**Department:** Sales | **Location:** Building A, Floor 1  
**Contact:** x5545  
**Priority:** Medium  

---

## Problem Summary
Kyle Morgan received a new phone and needed to add his work email account. The default email app settings were not connecting, and he was unsure what server information to use. His phone had internet access and personal email was working, but the work account would not authenticate.

This prevented him from checking work email while traveling for sales activities.

---

## Environment
- Android mobile device  
- Work email hosted on Exchange  
- ServiceDesk Simulator ticketing system  
- Documentation Station → Email & Exchange → Email Setup  

---

## Troubleshooting Steps
- Opened **Documentation Station** and navigated to **Email & Exchange → Email Setup**.  
- Initiated chat with the user to confirm device type.  
- User confirmed they were using an **Android** device.  
- Provided step‑by‑step setup instructions from the official documentation:

  1. Open **Settings → Accounts → Work email account**  
  2. Tap **Account Settings** or **Server Settings**  
  3. Under **Incoming Server**, update:  
     - Server: `mail.servicedesk-simulator.com`  
     - Port: `443`  
     - Security Type: `SSL/TLS`  
  4. Tap **Done/Save** and allow the account to re-sync  

- User followed the instructions and confirmed the account connected successfully.

---

## Root Cause
The user’s new phone did not automatically detect the correct **Exchange server settings**, requiring manual configuration.

---

## Resolution
- Verified device type  
- Provided correct server, port, and security settings  
- Guided user through Android email configuration  
- User successfully added work email account  
- Confirmed email syncing normally  

---

## Verification
- User confirmed they can send and receive work email  
- No further issues reported  

---

## What I Learned
- Always confirm the user’s device type before giving setup instructions  
- Exchange accounts often require manual server settings on new devices  
- Documentation Station provides accurate, standardized scripts for mobile setup  

