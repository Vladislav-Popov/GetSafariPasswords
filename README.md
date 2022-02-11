# Update: macOS Monterey added a native export function for your keychain.  
Use Settings - Passwords - Export passwords.

# GetSafariPasswords
Give full access to the "Script editor" in the system settings - protection and security - universal access.

Steps:
- Open the script with Script Editor
- Launch Safari
- Open Safari's preferences and navigate to the Passwords tab
- Unlock the dialog so your list of credentials is visible
- Switch back to Script Editor and hit its Run button
If all is successful, it will cycle through your rows of login credentials, and export them to a file on your Desktop named pm_export.csv. 

by MrC

