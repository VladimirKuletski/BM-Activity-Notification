# BM-Avtivity-Notification

Prototype for parsing BM activity messages using PowerShell (more or less native on Windows).
WS connection used.

Activity on group of interest should be highlighted using windows notifications.

Heavily relies on BM LastHeard data (often fails).

Uses:
* $ID_to_monitor to set group of interest ID
* $ID_to_exclude to set you personal ID (to exclude from notifications)
* Verbose mode is turned on by default (comment line 1 to mute console messages)

Parts of the code has been taken from:
- https://wragg.io/powershell-slack-bot-using-the-real-time-messaging-api/
- https://github.com/proxb/PowerShell_Scripts/blob/master/Invoke-BalloonTip.ps1

Should work Windows 8+
Has been tested Windows 10
