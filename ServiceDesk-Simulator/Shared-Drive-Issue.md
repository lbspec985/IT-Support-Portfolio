1.Problem Summary
User reported she was unable to access her mapped network drives and received the error: “Network Path Was Not Found.”

2.Troubleshooting Steps
--User‑Performed Troubleshooting

--Restarted computer (no change)

--Confirmed internet and email access

--Reported all mapped drives showing as disconnected

Technician Troubleshooting
--Verified user account in Active Directory: enabled, correct group membership, correct shared drive permissions

--Opened Server Room view and observed a network alert

--Contacted ISP via Teams

--ISP confirmed an active outage due to a fiber cut with a 2–3 hour ETA

--Notified user of the outage and advised to wait for restoration

--After ISP restored service, asked user to retry — user still unable to access drives

--Connected to user’s device via Remote Support

--Observed user’s VPN client was not connected

--Connected VPN for the user

--Confirmed user regained access to mapped drives

3. Root Cause
Primary: ISP fiber cut causing network outage, preventing remote users from reaching internal file servers.
Secondary: User’s VPN was disconnected, blocking access even after the outage was resolved.

4. Resolution
Informed user of ISP outage and provided ETA
After restoration, reconnected user’s VPN
Verified user successfully accessed mapped drives

5. What I Learned
Outages can create multiple symptoms, but only one is the true root cause
Remote users require VPN connectivity to access internal resources
Always re‑test after an outage because secondary issues may appear
Clear communication with ISPs and users is essential during outages
