Cloud contains a multitude of commands to use at your disposal. All commands are set up for specific Discord roles, which are automatically created and added into your server by Cloud. 

!!!
If you just invited Cloud to your server, you will need to run a specific command to initialize the roles
!!!

Here is a full breakdown of each command available with Cloud, including commands you will see but not have access to use:

=== Basic/Public Commands
<b>/close-cloud-ticket</b> : Closes the ticket you are currently in. Optionally, you are able to log a transcript of tickets made in your server by copying your transcript channel ID and inputting that into the transcript channel box.

!!!warning Warning
You must be in Discord Developer mode to copy the channel ID
!!!

<b>/help</b> : Sends an embed response from Cloud with basic information of some commands, features, and how to trigger some responses from Cloud.

<b>/info</b> : Sends an embed response from Cloud with a small introduction to itself, basic version information, notes on features and contributing testers, and two links; one to donate for Cloud's developement, and a link to Cloud's Offical Support Discord Server.

!!!tip Tip
Join the support server for better assistance and up-to-date details on all new things Cloud
!!!

<b>/open-cloud-ticket</b> : Starts the process of opening a ticket using Cloud in your server. 

<b>/close-cloud-ticket</b> : Closes the ticket you are in.
===

=== Mod Commands
!!! Mod Logging
All Mod Commands have the option of being logged by hooking up a mod log channel to Cloud
!!!

<b>/ban</b> : Bans selected user from your Discord server. Optionally, you are able to provide a reason.

<b>/kick</b> : Kicks selected user from your Discord server. Optionally, you are able to provide a reason. 

<b>/purge</b> : Mass deletes either a specified amount of messages or all. 

!!!danger Danger
The 'All' option does not work due to a bug. Only use the 'Amount' option until we are able to fix this, in an upcoming update.
!!!

<b>/remove-timeout</b> : Removes a timeout from a user if they are timedout in your Discord server. Optionally, you are able to provide a reason.

<b>/timeout</b> : Timeout a user in your Discord server. Optionally, you are able to provide a reason.

!!!info Info
The interval for timeouts are in minutes. 
Ex. 120 = 2 hour timeout
!!!

<b>/unban</b> : Unbans a user from your Discord server. Note that this only support Discord User IDs at this time. 

<b>/ticket-panel</b> : Posts the Cloud Ticket panel in your desired channel.

!!!note Note
This can only be used by the server owner
!!!
===

=== Bot Owner Commands

!!!danger Danger
No one can use these commands but the bot owner. This section is just for documentation purposes.
!!!

<b>/patchnotes</b> : Creates and posts an embed message of the latest patch notes for Cloud. This includes the new version build number, what was added, adjusted, changed, removed, and more. 

<b>/postimage</b> : Manually tell Cloud to post a random image in the central image channel.

<b>/restart</b> : Turns off Cloud, then turns it back on.

<b>/shutdown</b> : Completely shuts down, turning off Cloud.

<b>/status</b> : Checks and informs if there is a scheduled update, restart, or shutdown for Cloud.

<b>/update</b> : Updates the bot by updating the code from a local folder, then restarts and starts up again.

<b>/updatephoto</b> : Updates the bot database to upload any new pictures to the bot database.

===