Vendor: Fortinet
================
### Product: [Fortinet UTM](../ds_fortinet_fortinet_utm.md)
### Use-Case: [Privileged Activity](../../../../UseCases/uc_privileged_activity.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   6   |   3    |     3      |     13      |   13    |

| Event Type     | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Models                                                                                                                                                                      |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| app-activity   | <b>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions</b><br> ↳ <b>EM-InB-Ex</b>: A user has been given mailbox permissions for an executive user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>APP-F-SA-NC</b>: New service account access to application<br> ↳ <b>APP-GOb-A</b>: Abnormal access to application object for peer group<br> ↳ <b>APP-AT-PRIV</b>: Non-privileged user performing privileged application activity<br> ↳ <b>APP-ObT-PRIV</b>: Non-privileged user accessing privileged application object |  • <b>APP-ObT-PRIV</b>: Privileged application objects<br> • <b>APP-AT-PRIV</b>: Privileged application activities<br> • <b>APP-GOb</b>: Application objects per peer group |
| security-alert | <b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>ALERT-EXEC</b>: Security violation by Executive                                                                                                                                                                                                                                                                                                                                                                                                                              |                                                                                                                                                                             |