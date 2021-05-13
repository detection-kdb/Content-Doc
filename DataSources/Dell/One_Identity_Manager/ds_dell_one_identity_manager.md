Vendor: Dell
============
Product: One Identity Manager
-----------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  59   |   31   |     7      |      3      |    3    |

|                                           Use-Case                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                      | MITRE TTP                                                                                                                                                            | Content                                                                                                                                 |
|:--------------------------------------------------------------------------------------------:| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                                                       | [<ul><li>20 Rules</li></ul><ul><li>13 Models</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Abnormal_Authentication_&_Access.md) |
|             [Account Manipulation](../../../UseCases/uc_account_manipulation.md)             |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>                                                                                            | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Account_Manipulation.md)               |
|               [Brute Force Attack](../../../UseCases/uc_brute_force_attack.md)               |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1003 - OS Credential Dumping<br>T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>                                                                          | [<ul><li>5 Rules</li></ul><ul><li>4 Models</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Brute_Force_Attack.md)                 |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                                                       | [<ul><li>19 Rules</li></ul><ul><li>10 Models</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Compromised_Credentials.md)          |
|                      [Data Access](../../../UseCases/uc_data_access.md)                      |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                           | [<ul><li>16 Rules</li></ul><ul><li>10 Models</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Data_Access.md)                      |
|                        [Data Leak](../../../UseCases/uc_data_leak.md)                        |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1114.003 - Email Collection: Email Forwarding Rule<br>                                                                                                              | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Data_Leak.md)                                                    |
|                          [Evasion](../../../UseCases/uc_evasion.md)                          |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>                                                                                                                               | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Evasion.md)                                                      |
|                          [Malware](../../../UseCases/uc_malware.md)                          |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1078 - Valid Accounts<br>T1204 - User Execution<br>                                                                                                                 | [<ul><li>5 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Malware.md)                            |
|                  [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)                  |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>                                                                  | [<ul><li>7 Rules</li></ul><ul><li>3 Models</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Privilege_Abuse.md)                    |
|             [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)             |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1003 - OS Credential Dumping<br>T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br> | [<ul><li>8 Rules</li></ul><ul><li>5 Models</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Privilege_Escalation.md)               |
|              [Privileged Activity](../../../UseCases/uc_privileged_activity.md)              |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>                                                                  | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Privileged_Activity.md)                                          |
|                       [Ransomware](../../../UseCases/uc_ransomware.md)                       |  account-password-change<br> ↳ [cef-scbpam-account-password-change](Parsers/parserContent_cef-scbpam-account-password-change.md)<br><br> account-switch<br> ↳ [cef-scbpam-account-switch](Parsers/parserContent_cef-scbpam-account-switch.md)<br><br> app-activity<br> ↳ [cef-scbpam-app-activity](Parsers/parserContent_cef-scbpam-app-activity.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                           | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_dell_one_identity_manager_Ransomware.md)                                                   |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access                                                          | Discovery | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> |           |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |