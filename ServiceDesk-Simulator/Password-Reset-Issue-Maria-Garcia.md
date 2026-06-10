# Password Reset Issue — Maria Garcia

**Reported By:** Maria Garcia (mgarcia@servicedesk-simulator.com)  
**Department:** Engineering | **Location:** Floor 3  
**Contact:** x6102  
**Priority:** High  

---

<bold>Problem Summary</bold>
Maria Garcia reported that after returning from a 3‑week vacation, she was unable to log in to her workstation. The system indicated that her password had expired and required a change, but she was unable to complete the password change from the login screen. She had not logged in since late January. This issue prevented her from accessing her development environment, and she is the lead developer on a payment processing module with a sprint deadline on Friday.

---

<bold>Environment</bold>
- Windows workstation  
- Active Directory domain environment  
- MFA authentication required for password resets  
- ServiceDesk Simulator ticketing system  

---

<bold>Troubleshooting Steps</bold>
- **[Verified user identity](ca://s?q=Verify_user_identity_for_password_reset)** by sending a verification code through the Authentication tab; Maria confirmed the code via the company IT chat.  
- **[Opened Active Directory](ca://s?q=Check_if_account_is_locked_out)** and located Maria Garcia’s user account.  
- Observed that the **password was flagged as expired**.  
- Used the **Authentication** tab to send a verification code and confirm identity.  
- Generated and provided a **temporary password** for Maria to log in.  
- Instructed Maria to sign in with the temporary password and complete the password change process.  
- User successfully logged in and updated her password.  
- Confirmed she could access her development environment and resume work.

---

<bold>Root Cause</bold>
Maria’s password expired during her 3‑week absence, and Windows would not allow her to complete the password change from the login screen.

---
 <bold>Resolution</bold>
- Verified identity  
- Reset password in Active Directory  
- Provided temporary password  
- User logged in successfully and created a new password  
- Confirmed full access restored  

---

 <bold>Verification</bold>
- User confirmed successful login  
- User confirmed access to dev environment  
- No further issues reported  

---

<bold>What I Learned</bold>
- Password expiration can prevent login even when the user knows their old password  
- Identity verification is required before performing any password reset  
- Temporary passwords are the safest way to restore access  
- Clear communication ensures the user completes the password change successfully  

