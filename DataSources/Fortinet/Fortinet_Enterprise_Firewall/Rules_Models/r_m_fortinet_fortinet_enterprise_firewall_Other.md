Vendor: Fortinet
================
### Product: [Fortinet Enterprise Firewall](../ds_fortinet_fortinet_enterprise_firewall.md)
### Use-Case: [Other](../../../../UseCases/uc_other.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  67   |   29   |     7      |      6      |    6    |

| Event Type          | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| app-activity        | <br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br><br><b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>EM-InB-Ex</b>: A user has been given mailbox permissions for an executive user<br> ↳ <b>EM-InRule-EX</b>: User has created an inbox forwarding rule to forward email to an external domain email<br> ↳ <b>EM-InRule-Public</b>: User has created an inbox forwarding rule to forward email to a public email domain<br> ↳ <b>InB-Perm-N-F</b>: First time a user has given mailbox permissions on another mailbox that is not their own<br> ↳ <b>InB-Perm-N-A</b>: Abnormal for user to give mailbox permissions<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>AE-UA-F</b>: First activity type for user<br> ↳ <b>NEW-USER-F</b>: User with no event history<br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account<br> ↳ <b>APP-UApp-F</b>: First login or activity within an application for user<br> ↳ <b>APP-UApp-A</b>: Abnormal login or activity within an application for user<br> ↳ <b>APP-AppU-F</b>: First login to an application for a user with no history<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application<br> ↳ <b>APP-AppG-F</b>: First login to an application for group<br> ↳ <b>APP-GApp-A</b>: Abnormal login to an application for group<br> ↳ <b>APP-UTi</b>: Abnormal user activity time<br> ↳ <b>APP-UAg-F</b>: First user agent string for user<br> ↳ <b>APP-UAg-2</b>: Second new user agent string for user<br> ↳ <b>APP-UAg-3</b>: More than two new user agents used by the user in the same session<br> ↳ <b>APP-UsH-F</b>: First source asset for user in application<br> ↳ <b>APP-UsH-A</b>: Abnormal source asset for user in application<br> ↳ <b>APP-UOb-F</b>: First access to application object for user<br> ↳ <b>APP-UOb-A</b>: Abnormal access to application object for user<br> ↳ <b>APP-GOb-F</b>: First access to application object for peer group<br> ↳ <b>APP-GOb-A</b>: Abnormal access to application object for peer group<br> ↳ <b>APP-UappA-F</b>: First application activity for user<br> ↳ <b>APP-UappA-A</b>: Abnormal application activity for user<br> ↳ <b>APP-GappA-F</b>: First application activity for peer group<br> ↳ <b>APP-GappA-A</b>: Abnormal application activity for peer group<br> ↳ <b>APP-AA-F</b>: First application activity in the organization<br> ↳ <b>APP-AA-A</b>: Abnormal activity in application for the organization<br> ↳ <b>APP-UId-F</b>: First use of client Id for user<br> ↳ <b>APP-IdU-F</b>: Reuse of client Id<br> ↳ <b>APP-UMime-F</b>: First mime type for user<br> ↳ <b>APP-UMime-A</b>: Abnormal mime type for user<br> ↳ <b>APP-GMime-F</b>: First mime type for peer group<br> ↳ <b>APP-GMime-A</b>: Abnormal mime type for peer group<br> ↳ <b>APP-OMime-F</b>: First mime type for organization<br> ↳ <b>APP-OMime-A</b>: Abnormal mime type for organization<br> ↳ <b>APP-AppSz-F</b>: First application access from network zone<br> ↳ <b>APP-AT-PRIV</b>: Non-privileged user performing privileged application activity<br> ↳ <b>APP-ObT-PRIV</b>: Non-privileged user accessing privileged application object<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UC-A</b>: Abnormal activity from country for user<br> ↳ <b>UA-GC-F</b>: First activity from country for group<br> ↳ <b>UA-OC-F</b>: First activity from country for organization<br> ↳ <b>UA-GC-new</b>: Abnormal country for group by new user<br><br><b>T1188 - T1188</b><br> ↳ <b>Auth-Tor-Shost</b>: User authentication or login from a known TOR IP<br> ↳ <b>Auth-Blacklist-Shost</b>: User authentication or login from a known blacklisted IP<br> ↳ <b>Auth-Ransomware-Shost</b>: User authentication or login from a known ransomware IP |  • <b>EM-InB-Perm-N</b>: Models users who give mailbox permissions<br> • <b>APP-ObT-PRIV</b>: Privileged application objects<br> • <b>APP-AT-PRIV</b>: Privileged application activities<br> • <b>APP-AppSz</b>: Source zones per application<br> • <b>APP-OMime</b>: Mime types for organization<br> • <b>APP-GMime</b>: Mime types per peer group<br> • <b>APP-UMime</b>: Mime types per user<br> • <b>APP-IdU</b>: User per Client Id<br> • <b>APP-UId</b>: Client Id per User<br> • <b>APP-AA</b>: Activity per application<br> • <b>APP-GappA</b>: Application activity per peer group<br> • <b>APP-UappA</b>: Application activity per user<br> • <b>APP-GOb</b>: Application objects per peer group<br> • <b>APP-UOb</b>: Application objects per user<br> • <b>APP-UsH</b>: User's machines accessing applications<br> • <b>APP-UAg</b>: User Agent Strings<br> • <b>APP-UTi</b>: Application activity time for user<br> • <b>APP-GApp</b>: Group Logons to Applications<br> • <b>APP-AppG</b>: Groups per Application<br> • <b>APP-AppU</b>: User Logons to Applications<br> • <b>APP-UApp</b>: Applications per User<br> • <b>UA-GC</b>: Countries for peer groups<br> • <b>UA-OC</b>: Countries for organization<br> • <b>UA-UC</b>: Countries for user activity<br> • <b>AE-UA</b>: All activity for users |
| app-activity-failed | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account<br><br><b>T1188 - T1188</b><br> ↳ <b>Auth-Tor-Shost-Failed</b>: User authentication or login failure from a known TOR IP<br> ↳ <b>Auth-Blacklist-Shost-Failed</b>: User authentication or login failure from a known blacklisted IP<br> ↳ <b>Auth-Ransomware-Shost-Failed</b>: User authentication or login failure from a known ransomware IP                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| netflow-connection  | <b>T1046 - Network Service Scanning</b><br> ↳ <b>NETFLOW-OsH-SweepScan-F</b>: First time for asset to access 20 assets in 10 seconds<br> ↳ <b>NETFLOW-OsH-SweepScan-A</b>: Abnormal for asset to access 20 assets in 10 seconds<br> ↳ <b>NETFLOW-OsH-PortScan-F</b>: First vertical port scan for asset<br> ↳ <b>NETFLOW-OsH-PortScan-A</b>: Abnormal vertical port scan for asset<br><br><b>T1043 - T1043</b><br> ↳ <b>NETFLOW-dZdP-LowPort-F</b>: First time access to this port in this zone<br> ↳ <b>NETFLOW-dZdP-LowPort-A</b>: Abnormal access to this port in this zone<br> ↳ <b>NETFLOW-dHdP-LowPort-F</b>: First time access to this port in this asset<br> ↳ <b>NETFLOW-dHdP-LowPort-A</b>: Abnormal access to this port in this asset<br><br><b>T1065 - T1065</b><br> ↳ <b>A-NETFLOW-sHdP-F</b>: First time access of this port by this asset<br> ↳ <b>A-NETFLOW-SP-F</b>: Service running on port used by asset<br> ↳ <b>NETFLOW-sHdP-Server-F</b>: First/Abnormal access of this port by this server<br> ↳ <b>NETFLOW-dZdP-Service-F</b>: First time access to this service in this zone<br> ↳ <b>NETFLOW-dZdP-Service-A</b>: Abnormal access to this service in this zone<br><br><b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>A-NETFLOW-BitTorrent</b>: Asset accessed BitTorrent application                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |  • <b>A-NETFLOW-OsH-Scanners</b>: Assets that access multiple assets within seconds<br> • <b>A-NETFLOW-dHdP</b>: Destination Ports per asset<br> • <b>A-NETFLOW-dZdP</b>: Destination Ports per zone<br> • <b>A-NETFLOW-sHdP</b>: Ports accessed by this asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |