Vendor: APC
===========
Product: APC
------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  41   |   12   |     9      |      2      |    2    |

|                Use-Case                | Activity Types                                                                                                                                                                                                                                                      | Event Types/Parsers                                                                                                                                                               | MITRE TTP                                                                                                                                                                                                                                                | Content                                                                                    |
|:--------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Activity Time  and Type</li><li>Asset Logon and Access</li><li>Credential Switch Activity</li><li>Endpoint Activity</li><li>Executives</li><li>Network zones and Location Access</li><li>Pass The Hash and Golden Ticket</li><li>Process Activity</li></ul> |  network-alert<br> ↳ [apc-network-alert](Parsers/parserContent_apc-network-alert.md)<br><br> remote-logon<br> ↳ [apc-remote-logon](Parsers/parserContent_apc-remote-logon.md)<br> | T1003 - OS Credential Dumping<br>T1021 - Remote Services<br>T1068 - Exploitation for Privilege Escalation<br>T1075 - T1075<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1188 - T1188<br>T1204 - User Execution<br>T1208 - T1208<br> | [<ul><li>41 Rules</li></ul><ul><li>12 Models</li></ul>](Rules_Models/r_m_apc_apc_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                     | Credential Access                                                          | Discovery | Lateral Movement                                                     | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------- | ---------- | ------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> |           | [Remote Services](https://attack.mitre.org/techniques/T1021)<br><br> |            |                     |              |        |