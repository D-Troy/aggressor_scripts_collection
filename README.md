# aggressor_scripts_collection
Collection of various aggressor scripts for Cobalt Strike from awesome people. Will be sure to update this repo with credit to each person.

## AVQuery.cna
### Author: @r3dQu1nn
Queries the registry for AV installed

## All_In_One.cna
### Author: @r3dQu1nn
Persistence, Enumeration, Lateral Movement and Logging Aggressor Script

## ArtifactPayloadGenerator.cna
### Author: @r3dQu1nn
Generates every type of Stageless/Staged Payload based off a HTTP/HTTPS Listener

## CertUtilWebDelivery.cna
### Author: @r3dQu1nn
CertUtil Scripted Web Delivery (Stageless)

## CheckLAdminContext.ps1
Requirement for Initial-LAdminCheck.cna

## DA-Watch.cna
### Author: @Bretiz
Perform the same DA monitoring but using all Aggressor script to perform DA Group checks

## Initial-DACheck.cna
### Author: @Killswitch-GUI
Currently uses a PowerShell based check, combined with an aggressor script to check for the initial agent user name. While using .NET 3.5 to perform Domain Group enumeration (PowerShell 2+ safe). This allows for alerting on Pen-Test of a DA level beacons

## Initial-LAdminCheck.cna
### Author: @Killswitch-GUI
This script will Auto check for LocalAdmin User on intial agent

## Invoke-DACheck.ps1
### Author: @Killswitch-GUI
Requirement for Invoke-DACheck.cna

## Logger.cna
### Author: @r3dQu1nn
Logging script that captures all the Beacon outputs. Formats the Beacon input line to display timestamps. Use with logs.py to export all the logs for each operator.

## apache-style-weblog-output.cna
### Author: @bluescreenofjeff
Script to write weblog entries to an Apache-like format

## backdoor_accounts.cna
### Author: ???
Adds the guest account to the local admins or domain and enterprise admins group

## beaconSMS.cna
### Author: @424f424f
Receive SMS alert upon new beacons

## beacon_to_empire.cna
### Author: @bluescreenofjeff
Send your beacons to an empire listener

## beaconestablishednote.cna
### Author: ???
Sets a beacons note to first seen date and time stamp

## beaconid_note.cna
### Author: ???
Sets a beacons note to its beacon ID value

## beaconpire.cna
### Author: @bluescreenofjeff
An Aggressor script used to control Empire listeners and pass sessions between Cobalt Strike and Empire.

## bot.cna
### Author: ???
Cobalt Strike bot that will welcome users to your teamserver, play ping pong, list beacons by ID, list listeners, PsExec from the event log, automatically bypass UAC, screenshot all beacons

## checkin_jobs_context.cna
### Author: @bluescreenofjeff
Adds context menu options to run "checkin" or "jobs" on Beacon session to help detect stale beacons in bulk

## credocalypse.cna
### Author: ramen0x3f
Monitor beacons and pick off users as they log in

## custom_defaults.cna
### Author: 001SPARTaN
Custom defaults for Cobalt Strike

## dcom_lateral_movement.cna
### Author: ???
Lateral movement techniques based on research by enigma0x3 (Matt Nelson)

## eventlog-to-slack.cna
### Author: @bluescreenofjeff
Script to send event log events to Slack

## forcecheckin.cna
### Author: @bluescreenofjeff
Forces SMB Beacons to check-in on a specified interval

## guest-to-admin.cna
### Author: ???
Enable and add guest account to local admins group

## loader.cna
### Author: @_RastaMouse 
Loads the "elevate" directory into Cobalt Strike

## lulz.cna
### Author: ???
Various annoying red team attacks

## mass-dcsync.cna
### Author: @bluescreenofjeff
Mass DCSync a list of usernames from the specified domain

## mimikatz-every-30min.cna
### Author: @bluescreenofjeff
Runs the mimikatz logonpasswords alias on all beacons

## mimikatz-timestamp-note-BETA.cna
### Author: @bluescreenofjeff
Adds a timestamp to the source column in new credentials

## misc.cna
### Author: ???
Various capabilities to add to Cobalt Strike

## persistence.cna
### Author: Tyler Rosonke
Various persistence additions

## persistence-1.cna
### Author: @bluescreenofjeff
Various persistence additions

## ping_aliases.cna
### Author: @bluescreenofjeff
Alias for "qping" to "shell ping -n 1 [target]" and "smbscan" to "portscan [target] 445 none"

## powershell.cna
### Author: ???
Aliases for PowerUp and PowerView

## save_log.cna
### Author: ramen0x3f
Aggressor script to simplify exporting command output

## say.cna
### Author: ???
Create a audio alert on MacOS for new admin context beacons

## service-reboot.cna
### Author: ???
Create persistence via new service

## silver-tickets.cna
### Author: @bluescreenofjeff
GUI to make Silver Tickets for a session. monitors output for machine hashes and adds them to the cred store

## slack-notify-beacon.cna
### Author: @bluescreenofjeff
Send alerts to slack channel for new beacons

## slack-notify-webhit.cna
### Author: @bluescreenofjeff
Send alerts to slack channel for webhits

## sleeptimer.cna
### Author: @bluescreenofjeff
Provides a configuration to automatically set sleep interval based on the time

## sticky-keys.cna
### Author: ???
Create a sticky keys backdoor

## timestamped_activitylog_export.cna
### Author: @bluescreenofjeff
Output all event and activity logs with human-readable timestamp to activitylog.txt in your working directory

## ANGRYPUPPY (folder)
### Author: @vysecurity
Bloodhound Attack Path Execution for Cobalt Strike

