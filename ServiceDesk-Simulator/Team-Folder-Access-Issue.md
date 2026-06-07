<strong>Problem Summary</strong>:Kavita Patel transferred from Engineering to IT Infrastructure and needs her access updated for the new role, with old Engineering permissions removed

<strong>Troubleshooting Steps</strong>:
Opened the user’s AD profile to verify identity and current access.

Checked Group Memberships under the Groups tab.

Confirmed the user was still a member of Engineering and did not have IT Infrastructure access.

Added the user to the IT Infrastructure group to grant correct permissions for the new role.

Removed the user from the Engineering group to revoke old access and comply with security policy.

Verified the changes were applied successfully in AD.

Noted that the user will need to log out and back in for the new token to apply.

<strong>Root Cause</strong>:User’s department transfer was not yet reflected in Active Directory group memberships, leaving her with outdated Engineering access and missing IT Infrastructure permissions.

<strong>Resolution</strong>:
Added IT Infrastructure group membership

Removed Engineering group membership

Confirmed AD updated successfully

Ticket system displayed a green confirmation that access was corrected

<strong>Verification</strong>:
AD now shows correct group membership

No remaining Engineering access

Ticket system validated the fix

User will receive correct permissions upon next login

<strong>What I Learned</strong>:
Department transfers require both adding new access and removing old access

Group membership changes are the primary method of controlling access in AD

Always verify both sides: what the user should have and what they should not have

Removing outdated access is just as important as granting new access
