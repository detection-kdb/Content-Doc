Vendor: Microsoft
=================
### Product: [Microsoft Sysmon](../ds_microsoft_microsoft_sysmon.md)
### Use-Case: [Ransomware Detection](../../../../UseCases/uc_ransomware_detection.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  29   |   11   |     14     |      5      |    5    |

| Event Type      | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| dns-query       | <b>T1071.004 - Application Layer Protocol: DNS</b><br> ↳ <b>A-DNS-MALDOM-QUERY</b>: DNS query for blacklisted domain from this asset<br><br><b>T1568.002 - Dynamic Resolution: Domain Generation Algorithms</b><br> ↳ <b>A-DNS-DGADOM-QUERY</b>: DNS query for DGA domain from this asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| file-write      | <b>T1204 - User Execution</b><br> ↳ <b>EPA-TEMP-DIRECTORY-F</b>: First execution of this process from a temporary directory on this asset<br> ↳ <b>EPA-TEMP-DIRECTORY-A</b>: Abnormal execution of this process from a temporary directory<br> ↳ <b>FA-TEMP-DIRECTORY-F</b>: First time process has been executed from a temporary directory by this user during file activity<br> ↳ <b>FA-TEMP-DIRECTORY-A</b>: Abnormal process has been executed from a temporary directory by this user during file activity                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  • <b>FA-UP-TEMP</b>: Process executable TEMP directories for this user during file activity<br> • <b>A-EPA-UP-TEMP</b>: Processes executed from TEMP directories on this asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| process-created | <b>T1003 - OS Credential Dumping</b><br> ↳ <b>Mimikatz-process</b>: A highly dangerous attacker tool, Mimikatz, has been used<br><br><b>T1087.001 - Account Discovery: Local Account</b><b>T1087.002 - Account Discovery: Domain Account</b><br> ↳ <b>A-EPA-UP-CENUM</b>: Abnormal number of unique credential enumeration tools run on this asset<br> ↳ <b>EPA-OU-CENUM-A</b>: Abnormal for this user to run credential enumeration tool<br><br><b>T1016 - System Network Configuration Discovery</b><b>T1057 - Process Discovery</b><b>T1082 - System Information Discovery</b><br> ↳ <b>EPA-OU-HENUM-F</b>: First user running host enumeration tool<br> ↳ <b>EPA-OU-HENUM-A</b>: Abnormal for this user to run host enumeration tool<br> ↳ <b>EPA-OH-HENUM-F</b>: Host running host enumeration tool for the first time<br> ↳ <b>EPA-OH-HENUM-A</b>: Abnormal for this host to run host enumeration tool<br><br><b>T1204 - User Execution</b><br> ↳ <b>A-EPA-HP-F</b>: First execution of process on asset<br> ↳ <b>A-EPA-HP-A</b>: Abnormal execution of process on asset<br> ↳ <b>A-EPA-ZP-A</b>: Abnormal execution of process for the asset in this zone<br> ↳ <b>A-EPA-ZP-F</b>: First execution of process for the asset in this zone<br> ↳ <b>A-EPA-OP-F</b>: First execution of process for the asset in this organization<br> ↳ <b>A-EPA-OP-A</b>: Abnormal execution of process for the asset in this organization<br> ↳ <b>EPA-OP-F</b>: First execution of process in this organization<br> ↳ <b>EPA-TEMP-DIRECTORY-F</b>: First time process has been executed from a temporary directory by this user during endpoint activity<br> ↳ <b>EPA-TEMP-DIRECTORY-A</b>: Abnormal process has been executed from a temporary directory by this user during endpoint activity<br><br><b>T1219 - Remote Access Software</b><br> ↳ <b>A-EPA-RAT-TSI</b>: TeamViewer remote desktop access service installed on this asset<br><br><b>T1036.005 - Masquerading: Match Legitimate Name or Location</b><br> ↳ <b>A-EPA-OPP-F</b>: First parent-process combination in this organization<br> ↳ <b>A-EPA-OPP-A</b>: Abnormal parent-process combination in this organization<br><br><b>T1036 - Masquerading</b><br> ↳ <b>A-EPA-HPP-F</b>: First parent-process combination on asset<br> ↳ <b>A-EPA-HPP-A</b>: Abnormal parent-process combination on asset<br><br><b>T1059.001 - Command and Scripting Interperter: PowerShell</b><br> ↳ <b>A-ALERT-COMPROMISED-POWERSHELL</b>: Powershell and security alerts |  • <b>EPA-OU-CENUM</b>: Users running credential enumeration tools<br> • <b>EPA-OH-HENUM</b>: Hosts on which host enumeration tools are run<br> • <b>EPA-OU-HENUM</b>: Users running host enumeration tools<br> • <b>EPA-UP-TEMP</b>: Process executable TEMP directories for this user during endpoint activity<br> • <b>EPA-OP</b>: Processes in the organization<br> • <b>A-EPA-UP-CENUM</b>: Unique credential enumeration tools run on this host<br> • <b>A-EPA-UP-TEMP</b>: Processes executed from TEMP directories on this asset<br> • <b>A-EPA-OPP</b>: Parent processes in the organization<br> • <b>A-EPA-HPP</b>: Parent processes per host on this asset<br> • <b>A-EPA-ZP</b>: Processes in the zone on asset |
| process-network | <b>T1204 - User Execution</b><br> ↳ <b>A-EPA-HP-F</b>: First execution of process on asset<br> ↳ <b>A-EPA-HP-A</b>: Abnormal execution of process on asset<br> ↳ <b>A-EPA-ZP-A</b>: Abnormal execution of process for the asset in this zone<br> ↳ <b>A-EPA-ZP-F</b>: First execution of process for the asset in this zone<br> ↳ <b>A-EPA-OP-F</b>: First execution of process for the asset in this organization<br> ↳ <b>A-EPA-OP-A</b>: Abnormal execution of process for the asset in this organization<br> ↳ <b>EPA-TEMP-DIRECTORY-F</b>: First time process has been executed from a temporary directory by this user during endpoint activity<br> ↳ <b>EPA-TEMP-DIRECTORY-A</b>: Abnormal process has been executed from a temporary directory by this user during endpoint activity<br><br><b>T1071 - Application Layer Protocol</b><br> ↳ <b>NET-TI-H-Outbound</b>: Outbound connection to a known malicious host<br> ↳ <b>NET-OdZ-Inbound-F</b>: First inbound connection to zone.<br> ↳ <b>NET-OdZ-Inbound-A</b>: Abnormal inbound connection to zone.<br><br><b>T1036.005 - Masquerading: Match Legitimate Name or Location</b><br> ↳ <b>A-EPA-OPP-F</b>: First parent-process combination in this organization<br> ↳ <b>A-EPA-OPP-A</b>: Abnormal parent-process combination in this organization<br><br><b>T1036 - Masquerading</b><br> ↳ <b>A-EPA-HPP-F</b>: First parent-process combination on asset<br> ↳ <b>A-EPA-HPP-A</b>: Abnormal parent-process combination on asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  • <b>EPA-UP-TEMP</b>: Process executable TEMP directories for this user during endpoint activity<br> • <b>A-NET-OdZ-Inbound</b>: Network zones with inbound communication in the organization<br> • <b>A-EPA-UP-TEMP</b>: Processes executed from TEMP directories on this asset<br> • <b>A-EPA-OPP</b>: Parent processes in the organization<br> • <b>A-EPA-HPP</b>: Parent processes per host on this asset<br> • <b>A-EPA-ZP</b>: Processes in the zone on asset                                                                                                                                                                                                                                                        |