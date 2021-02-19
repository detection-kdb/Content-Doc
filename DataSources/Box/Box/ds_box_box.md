Vendor: Box
===========
Product: Box
------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  54   |   7    |     5      |      8      |    8    |

|                Use-Case                | Activity Types                                                                                                                                                                                                                                                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | MITRE TTP                                                                                                                                                   | Content                                                                                   |
|:--------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Email Activity</li><li>Endpoint Activity</li><li>File Activity</li><li>Network zones and Location Access</li><li>Service Account Activity</li></ul> |  app-activity<br> ↳ [q-box-app-activity](Parsers/parserContent_q-box-app-activity.md)<br><br> app-login<br> ↳ [q-box-app-activity](Parsers/parserContent_q-box-app-activity.md)<br> ↳ [box-activity](Parsers/parserContent_box-activity.md)<br><br> file-delete<br> ↳ [q-box-app-activity](Parsers/parserContent_q-box-app-activity.md)<br> ↳ [box-activity](Parsers/parserContent_box-activity.md)<br> ↳ [box-skyformation-file-activity](Parsers/parserContent_box-skyformation-file-activity.md)<br><br> file-download<br> ↳ [q-box-app-activity](Parsers/parserContent_q-box-app-activity.md)<br> ↳ [box-activity](Parsers/parserContent_box-activity.md)<br> ↳ [cef-box-file-activity](Parsers/parserContent_cef-box-file-activity.md)<br> ↳ [box-skyformation-file-activity](Parsers/parserContent_box-skyformation-file-activity.md)<br><br> file-permission-change<br> ↳ [box-skyformation-file-activity](Parsers/parserContent_box-skyformation-file-activity.md)<br> ↳ [q-box-app-activity](Parsers/parserContent_q-box-app-activity.md)<br> ↳ [box-activity](Parsers/parserContent_box-activity.md)<br> ↳ [cef-box-file-activity](Parsers/parserContent_cef-box-file-activity.md)<br><br> file-read<br> ↳ [q-box-app-activity](Parsers/parserContent_q-box-app-activity.md)<br> ↳ [box-activity](Parsers/parserContent_box-activity.md)<br> ↳ [cef-box-file-activity](Parsers/parserContent_cef-box-file-activity.md)<br> ↳ [box-skyformation-file-activity](Parsers/parserContent_box-skyformation-file-activity.md)<br><br> file-upload<br> ↳ [cef-skyformation-file-activity](Parsers/parserContent_cef-skyformation-file-activity.md)<br> ↳ [q-box-app-activity](Parsers/parserContent_q-box-app-activity.md)<br> ↳ [box-activity](Parsers/parserContent_box-activity.md)<br> ↳ [box-skyformation-file-activity](Parsers/parserContent_box-skyformation-file-activity.md)<br><br> file-write<br> ↳ [cef-skyformation-file-activity](Parsers/parserContent_cef-skyformation-file-activity.md)<br> ↳ [q-box-app-activity](Parsers/parserContent_q-box-app-activity.md)<br> ↳ [box-activity](Parsers/parserContent_box-activity.md)<br> ↳ [box-skyformation-file-activity](Parsers/parserContent_box-skyformation-file-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1188 - T1188<br>T1204 - User Execution<br> | [<ul><li>54 Rules</li></ul><ul><li>7 Models</li></ul>](Rules_Models/r_m_box_box_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |