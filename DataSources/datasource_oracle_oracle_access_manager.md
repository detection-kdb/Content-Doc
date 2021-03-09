Vendor: Oracle
==============
Product: Oracle Access Manager
------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  33   |   4    |     3      |      4      |    4    |

|                                 Use-Case                                  | Activity Types                                                                                                                                                                                                    | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                     | MITRE TTP                                                        | Content                                              |
|:-------------------------------------------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Network zones and Location Access</li><li>Service Account Activity</li></ul> |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>   | <ul><li>25 Rules</li></ul><ul><li>4 Models</li></ul> |
|          [Internal Fraud](../UseCases/usecase_internal_fraud.md)          | <ul><li>Application Activity</li></ul>                                                                                                                                                                            |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>                                       | <ul><li>4 Rules</li></ul>                            |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Network zones and Location Access</li></ul>                                                                                                  |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>   | <ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>  |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                          |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br> | <ul><li>6 Rules</li></ul>                            |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | <ul><li>Service Account Activity</li></ul>                                                                                                                                                                        |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>                                       | <ul><li>1 Rules</li></ul>                            |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                          |  app-login<br> ↳ [s-oam-app-login-1](../Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [oracle-access-manager](../Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](../Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br> | <ul><li>6 Rules</li></ul>                            |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |