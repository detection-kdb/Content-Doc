Vendor: OAM
===========
Product: Oracle Access Manager
------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  24   |   5    |     6      |      8      |    8    |

|                                 Use-Case                                  | Activity Types                                                                                                     | Event Types/Parsers                                                                                                                                                                   | MITRE TTP                                                      | Content                                              |
|:-------------------------------------------------------------------------:| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Asset Logon and Access</li><li>Network zones and Location Access</li></ul> |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | <ul><li>10 Rules</li></ul><ul><li>4 Models</li></ul> |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | <ul><li>Network zones and Location Access</li></ul>                                                                |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | <ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>  |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | <ul><li>Asset Logon and Access</li></ul>                                                                           |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1188 - T1188<br>                                              | <ul><li>6 Rules</li></ul>                            |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li></ul>                                                                           |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1188 - T1188<br>                                              | <ul><li>6 Rules</li></ul>                            |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     |              |        |