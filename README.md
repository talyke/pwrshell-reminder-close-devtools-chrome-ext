### Dev Mode Reminder for Chrome (PowerShell Script)

This PowerShell script keeps an eye on your Chrome windows and gently reminds you to disable Developer Mode after you close YouTube — just in case you forget.

#### What It Does
- Checks if Chrome is running and if any open tab contains "YouTube" in the title
- When you close all YouTube tabs, it pops up a Windows message box reminder
- Helps you stay secure by nudging you to turn off Developer Mode once you're done
#### Requirements
- Windows 10/11 with PowerShell
- Google Chrome installed
- Developer Mode manually toggled ON at some point (this script won’t change it, just reminds you)
#### How to Use
- Copy the DevModeReminder.ps1 script to your preferred folder
- Right-click it → Run with PowerShell
- Let it run in the background while you browse
- When all YouTube tabs are closed, you'll see a reminder like this:
You closed YouTube. Remember to disable Chrome's Developer Mode if you enabled it for scripts!

#### Best Practices
- Only use Developer Mode when necessary
- Avoid installing unpacked extensions from untrusted sources
- Disable Developer Mode when browsing sensitive sites (banking, work accounts, etc.)
#### Bonus Tip
Want this to run at startup?
- Press Win + R, type shell:startup, and hit Enter
- Place a shortcut to DevModeReminder.ps1 in that folder
- You’ll now have passive reminders every time you log in
