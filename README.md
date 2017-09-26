# aggressor_scripts_collection
Collection of various aggressor scripts for Cobalt Strike from awesome people. Will be sure to update this repo with credit to each person.

### AVQuery.cna
Author: @r3dQu1nn
Queries the registry for AV installed

### All_In_One.cna
Author: @r3dQu1nn
Persistence, Enumeration, Lateral Movement and Logging Aggressor Script

### ArtifactPayloadGenerator.cna
Author: @r3dQu1nn
Generates every type of Stageless/Staged Payload based off a HTTP/HTTPS Listener

### CertUtilWebDelivery.cna
Author: @r3dQu1nn
CertUtil Scripted Web Delivery (Stageless)

### CheckLAdminContext.ps1
Requirement for Initial-LAdminCheck.cna

### DA-Watch.cna
Author: @Bretiz
Perform the same DA monitoring but using all Aggressor script to perform DA Group checks

### Initial-DACheck.cna
Author: @Killswitch-GUI
Currently uses a PowerShell based check, combined with an aggressor script to check for the initial agent user name. While using .NET 3.5 to perform Domain Group enumeration (PowerShell 2+ safe). This allows for alerting on Pen-Test of a DA level beacons

### Initial-LAdminCheck.cna
Author: @Killswitch-GUI
This script will Auto check for LocalAdmin User on intial agent

### Invoke-DACheck.ps1
Author: @Killswitch-GUI
Requirement for Invoke-DACheck.cna

### Logger.cna
Author: @r3dQu1nn
Logging script that captures all the Beacon outputs. Formats the Beacon input line to display timestamps. Use with logs.py to export all the logs for each operator.

