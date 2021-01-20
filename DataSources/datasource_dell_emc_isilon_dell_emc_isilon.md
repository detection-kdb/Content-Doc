Vendor: Dell EMC Isilon
=======================
Product: Dell EMC Isilon
------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  45   |   8    |     12     |     24      |   24    |

|                                 Use-Case                                  | Activity Types                                                                                                                                                                                | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | MITRE TTP                                                                                                                | Content                                              |
|:-------------------------------------------------------------------------:| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Asset Logon and Access</li><li>Credential Switch Activity</li><li>Network zones and Location Access</li><li>Pass The Hash and Golden Ticket</li></ul> |  file-delete<br> ↳ [dell-file-operations-2](../Parsers/parserContent_dell-file-operations-2.md)<br><br> file-read<br> ↳ [dell-file-operations-1](../Parsers/parserContent_dell-file-operations-1.md)<br> ↳ [dell-file-operations-4](../Parsers/parserContent_dell-file-operations-4.md)<br><br> file-write<br> ↳ [dell-file-operations-3](../Parsers/parserContent_dell-file-operations-3.md)<br> ↳ [json-dell-file-operations](../Parsers/parserContent_json-dell-file-operations.md)<br><br> remote-access<br> ↳ [dell-file-remote-access](../Parsers/parserContent_dell-file-remote-access.md)<br> | T1003 - OS Credential Dumping<br>T1021 - Remote Services<br>T1075 - T1075<br>T1078 - Valid Accounts<br>T1208 - T1208<br> | <ul><li>20 Rules</li></ul><ul><li>3 Models</li></ul> |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | <ul><li>Asset Logon and Access</li><li>Credential Switch Activity</li><li>Critical System Activity</li><li>Network zones and Location Access</li></ul>                                        |  file-delete<br> ↳ [dell-file-operations-2](../Parsers/parserContent_dell-file-operations-2.md)<br><br> file-read<br> ↳ [dell-file-operations-1](../Parsers/parserContent_dell-file-operations-1.md)<br> ↳ [dell-file-operations-4](../Parsers/parserContent_dell-file-operations-4.md)<br><br> file-write<br> ↳ [dell-file-operations-3](../Parsers/parserContent_dell-file-operations-3.md)<br> ↳ [json-dell-file-operations](../Parsers/parserContent_json-dell-file-operations.md)<br><br> remote-access<br> ↳ [dell-file-remote-access](../Parsers/parserContent_dell-file-remote-access.md)<br> | T1021 - Remote Services<br>T1078 - Valid Accounts<br>                                                                    | <ul><li>12 Rules</li></ul><ul><li>2 Models</li></ul> |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | <ul><li>Endpoint Activity</li><li>Process Activity</li></ul>                                                                                                                                  |  file-delete<br> ↳ [dell-file-operations-2](../Parsers/parserContent_dell-file-operations-2.md)<br><br> file-read<br> ↳ [dell-file-operations-1](../Parsers/parserContent_dell-file-operations-1.md)<br> ↳ [dell-file-operations-4](../Parsers/parserContent_dell-file-operations-4.md)<br><br> file-write<br> ↳ [dell-file-operations-3](../Parsers/parserContent_dell-file-operations-3.md)<br> ↳ [json-dell-file-operations](../Parsers/parserContent_json-dell-file-operations.md)<br><br> remote-access<br> ↳ [dell-file-remote-access](../Parsers/parserContent_dell-file-remote-access.md)<br> | T1204 - User Execution<br>                                                                                               | <ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>  |
|                   [Other](../UseCases/usecase_other.md)                   | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                      |  file-delete<br> ↳ [dell-file-operations-2](../Parsers/parserContent_dell-file-operations-2.md)<br><br> file-read<br> ↳ [dell-file-operations-1](../Parsers/parserContent_dell-file-operations-1.md)<br> ↳ [dell-file-operations-4](../Parsers/parserContent_dell-file-operations-4.md)<br><br> file-write<br> ↳ [dell-file-operations-3](../Parsers/parserContent_dell-file-operations-3.md)<br> ↳ [json-dell-file-operations](../Parsers/parserContent_json-dell-file-operations.md)<br><br> remote-access<br> ↳ [dell-file-remote-access](../Parsers/parserContent_dell-file-remote-access.md)<br> | T1550 - Use Alternate Authentication Material<br>                                                                        | <ul><li>3 Rules</li></ul>                            |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | <ul><li>Asset Logon and Access</li><li>Executives</li></ul>                                                                                                                                   |  file-delete<br> ↳ [dell-file-operations-2](../Parsers/parserContent_dell-file-operations-2.md)<br><br> file-read<br> ↳ [dell-file-operations-1](../Parsers/parserContent_dell-file-operations-1.md)<br> ↳ [dell-file-operations-4](../Parsers/parserContent_dell-file-operations-4.md)<br><br> file-write<br> ↳ [dell-file-operations-3](../Parsers/parserContent_dell-file-operations-3.md)<br> ↳ [json-dell-file-operations](../Parsers/parserContent_json-dell-file-operations.md)<br><br> remote-access<br> ↳ [dell-file-remote-access](../Parsers/parserContent_dell-file-remote-access.md)<br> | T1021 - Remote Services<br>T1068 - Exploitation for Privilege Escalation<br>                                             | <ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>  |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | <ul><li>Endpoint Activity</li><li>Process Activity</li></ul>                                                                                                                                  |  file-delete<br> ↳ [dell-file-operations-2](../Parsers/parserContent_dell-file-operations-2.md)<br><br> file-read<br> ↳ [dell-file-operations-1](../Parsers/parserContent_dell-file-operations-1.md)<br> ↳ [dell-file-operations-4](../Parsers/parserContent_dell-file-operations-4.md)<br><br> file-write<br> ↳ [dell-file-operations-3](../Parsers/parserContent_dell-file-operations-3.md)<br> ↳ [json-dell-file-operations](../Parsers/parserContent_json-dell-file-operations.md)<br><br> remote-access<br> ↳ [dell-file-remote-access](../Parsers/parserContent_dell-file-remote-access.md)<br> | T1204 - User Execution<br>                                                                                               | <ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>  |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                               | Credential Access                                                          | Discovery | Lateral Movement                                                                                                                                               | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> |           | [Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br> |            |                     |              |        |