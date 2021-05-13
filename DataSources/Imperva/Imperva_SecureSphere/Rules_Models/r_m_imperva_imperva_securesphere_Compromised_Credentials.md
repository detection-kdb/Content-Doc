Vendor: Imperva
===============
### Product: [Imperva SecureSphere](../ds_imperva_imperva_securesphere.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  44   |   24   |     5      |     10      |   10    |

| Event Type       | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| app-login        | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-AppU-F</b>: First login to an application for a user with no history<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application<br> ↳ <b>APP-AppG-F</b>: First login to an application for group<br> ↳ <b>APP-GApp-A</b>: Abnormal login to an application for group<br> ↳ <b>APP-UAg-3</b>: More than two new user agents used by the user in the same session<br><br><b>T1078 - Valid Accounts</b><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |  • <b>APP-UAg</b>: User Agent Strings<br> • <b>APP-GApp</b>: Group Logons to Applications<br> • <b>APP-AppG</b>: Groups per Application<br> • <b>APP-AppU</b>: User Logons to Applications                                                                                                                                                                                                                                                                                                                                                                                                   |
| database-alert   | <b>T1213 - Data from Information Repositories</b><br> ↳ <b>DB-UN-ALERT-F</b>: First database alert name for user<br> ↳ <b>DB-UN-ALERT-A</b>: Abnormal database alert name for user<br> ↳ <b>DB-ON-ALERT-F</b>: First database alert name in the organization<br> ↳ <b>DB-ON-ALERT-A</b>: Abnormal database alert name in the organization<br> ↳ <b>DB-GN-ALERT-F</b>: First database alert name in the peer group<br> ↳ <b>DB-GN-ALERT-A</b>: Abnormal database alert name in the peer group<br> ↳ <b>DB-OU-ALERT-F</b>: First database alert triggered for this user in the organization<br> ↳ <b>DB-OU-ALERT-A</b>: Abnormal user triggering database alert in the organization<br> ↳ <b>DB-OG-ALERT-F</b>: First database alert triggered for peer group in the organization<br> ↳ <b>DB-OG-ALERT-A</b>: Abnormal peer group triggering database alert in the organization<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>DB-ZN-ALERT-A</b>: Abnormal database alert (by name) in the zone<br> ↳ <b>DB-ZN-ALERT-F</b>: First database alert (by name) in the zone<br> ↳ <b>DB-ZA-ALERT-F</b>: First database alert triggered for asset inb the zone<br> ↳ <b>DB-ZA-ALERT-A</b>: Abnormal asset triggering database alert for zone                                                                                                                                                                                                                                                                                                                                                    |  • <b>DB-OG-ALERT</b>: Peer groups triggering database alerts in the organization<br> • <b>DB-OU-ALERT</b>: Users triggering database alerts in the organization<br> • <b>DB-GN-ALERT</b>: Database alert names in the peer group<br> • <b>DB-ON-ALERT</b>: Database alert names in the organization<br> • <b>DB-UN-ALERT</b>: Database alert names for user<br> • <b>A-DB-ZA-ALERT</b>: Assets triggering database alerts in the zone<br> • <b>A-DB-ZN-ALERT</b>: Database alert names triggered in the zone<br> • <b>A-DB-ON-ALERT</b>: Database alert names triggered in the organization |
| failed-app-login | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-F-FL</b>: Failed login to application                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| network-alert    | <b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>A-IDS-OLA-F</b>: First network alert on asset with no previous alerts for organization<br> ↳ <b>A-IDS-ZLA-A</b>: Abnormal network alert for asset for zone<br> ↳ <b>A-IDS-OLZ-F</b>: First network alert for zone in the organization<br> ↳ <b>A-IDS-HdPort-A</b>: Abnormal network alert on port for asset<br> ↳ <b>A-IDS-ALERT-6</b>: Six distinct network alerts on asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  • <b>A-IDS-HdPort</b>: Destination ports on which network alerts have triggered for the asset<br> • <b>A-IDS-OLZ</b>: Zones in which network alerts are triggered in the organization<br> • <b>A-IDS-ZLA</b>: Assets that triggered network alerts in the zone<br> • <b>A-IDS-OLA</b>: Assets that triggered network alerts in the organization                                                                                                                                                                                                                                             |
| security-alert   | <b>T1078 - Valid Accounts</b><br> ↳ <b>SA-AN-ALERT-F</b>: First security alert name on the asset<br> ↳ <b>SA-ON-ALERT-F</b>: First security alert (by name) in the organization<br> ↳ <b>SA-ON-ALERT-A</b>: Abnormal security alert (by name) in the organization<br> ↳ <b>SA-ZN-ALERT-F</b>: First security alert (by name) in the zone<br> ↳ <b>SA-ZN-ALERT-A</b>: Abnormal security alert (by name) in the zone<br> ↳ <b>SA-HN-ALERT-F</b>: First security alert (by name) in the asset<br> ↳ <b>SA-HN-ALERT-A</b>: Abnormal security alert (by name) in the asset<br> ↳ <b>SA-OU-ALERT-F</b>: First security alert triggered for this user in the organization<br> ↳ <b>SA-OU-ALERT-A</b>: Abnormal user triggering security alert in the organization<br> ↳ <b>SA-OG-ALERT-F</b>: First security alert triggered for peer group in the organization<br> ↳ <b>SA-OG-ALERT-A</b>: Abnormal peer group triggering security alert in the organization<br> ↳ <b>SA-UA-F</b>: First security alert name for user<br> ↳ <b>SA-UA-A</b>: Abnormal security alert name for user<br> ↳ <b>SA-OA-F</b>: First security alert name in the organization<br> ↳ <b>SA-OA-A</b>: Abnormal security alert name in the organization<br><br><b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>A-ALERT-DISTINCT-NAMES</b>: Various security alerts on asset<br> ↳ <b>A-ALERT</b>: Security alert on asset<br><br><b>T1059.001 - Command and Scripting Interperter: PowerShell</b><br> ↳ <b>A-ALERT-COMPROMISED-POWERSHELL</b>: Powershell and security alerts |  • <b>SA-OA</b>: Security alert names in the organization<br> • <b>SA-UA</b>: Security alert names for user<br> • <b>SA-OG-ALERT</b>: Peer groups triggering security alerts in the organization<br> • <b>SA-OU-ALERT</b>: Users triggering security alerts in the organization<br> • <b>A-SA-HN-ALERT</b>: Security alert names triggered by the asset<br> • <b>A-SA-ZN-ALERT</b>: Security alert names triggered in the zone<br> • <b>A-SA-ON-ALERT</b>: Security alert names triggered in the organization<br> • <b>A-SA-AN-ALERT</b>: Security alert names on asset                      |