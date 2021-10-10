# BM-Avtivity-Notification

Prototype for parsing BM activity messages using PowerShell (more or less native on Windows).
WS connection used 

Activity on group of interest should be highlighted using windows notifications

Heavily relies on BM LastHeard data (often fails)

Uses
$ID_to_monitor to set group of interest ID
$ID_to_exclude to set you personal ID (to exclude from notifications)

Parts o code has been taken from:
- https://wragg.io/powershell-slack-bot-using-the-real-time-messaging-api/
- https://mcpmag.com/articles/2017/09/07/creating-a-balloon-tip-notification-using-powershell.aspx
