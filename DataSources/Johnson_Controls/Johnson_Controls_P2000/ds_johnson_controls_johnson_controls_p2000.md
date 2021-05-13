Vendor: Johnson Controls
========================
Product: Johnson Controls P2000
-------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  78   |   28   |     14     |      5      |    5    |

|                                           Use-Case                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | MITRE TTP                                                                                                                                                                                                                                                                                                                                                                                                                  | Content                                                                                                                                               |
|:--------------------------------------------------------------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>                                                                                                                                                                                                                                                                                                                                      | [<ul><li>23 Rules</li></ul><ul><li>13 Models</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Abnormal_Authentication_&_Access.md) |
|               [Brute Force Attack](../../../UseCases/uc_brute_force_attack.md)               |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1021.001 - Remote Services: Remote Desktop Protocol<br>T1110 - Brute Force<br>                                                                                                                                                                                                                                                                                                                                            | [<ul><li>5 Rules</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Brute_Force_Attack.md)                                           |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1059.001 - Command and Scripting Interperter: PowerShell<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                                                                                                                                                                   | [<ul><li>27 Rules</li></ul><ul><li>13 Models</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Compromised_Credentials.md)          |
|                      [Data Access](../../../UseCases/uc_data_access.md)                      |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                                                                                 | [<ul><li>4 Rules</li></ul><ul><li>4 Models</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Data_Access.md)                        |
|                          [Evasion](../../../UseCases/uc_evasion.md)                          |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>                                                                                                                                                                                                                                                                                                                                                                                     | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Evasion.md)                                                      |
|                 [Lateral Movement](../../../UseCases/uc_lateral_movement.md)                 |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1021.001 - Remote Services: Remote Desktop Protocol<br>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1075 - T1075<br>T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1550.002 - Use Alternate Authentication Material: Pass the Hash<br>T1550.003 - Use Alternate Authentication Material: Pass the Ticket<br>T1550.004 - Use Alternate Authentication Material: Web Session Cookie<br> | [<ul><li>11 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Lateral_Movement.md)                  |
|                          [Malware](../../../UseCases/uc_malware.md)                          |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>T1210 - Exploitation of Remote Services<br>                                                                                                                                                                                                                                                                                      | [<ul><li>9 Rules</li></ul><ul><li>4 Models</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Malware.md)                            |
|                [Physical Security](../../../UseCases/uc_physical_security.md)                |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                                                                                 | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Physical_Security.md)                                            |
|                  [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)                  |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                                                                                 | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Privilege_Abuse.md)                    |
|             [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)             |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1210 - Exploitation of Remote Services<br>                                                                                                                                                                                                                                                                                                                                                                                | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Privilege_Escalation.md)                                         |
|              [Privileged Activity](../../../UseCases/uc_privileged_activity.md)              |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                                | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Privileged_Activity.md)                                          |
|                       [Ransomware](../../../UseCases/uc_ransomware.md)                       |  account-password-change-failed<br> ↳ [auth0-password-change-failed](Parsers/parserContent_auth0-password-change-failed.md)<br><br> app-login<br> ↳ [auth0-login-success](Parsers/parserContent_auth0-login-success.md)<br><br> failed-logon<br> ↳ [auth0-login-failed-1](Parsers/parserContent_auth0-login-failed-1.md)<br> ↳ [auth0-login-failed](Parsers/parserContent_auth0-login-failed.md)<br><br> physical-access<br> ↳ [p2000-physical-badge-access](Parsers/parserContent_p2000-physical-badge-access.md)<br><br> security-alert<br> ↳ [lastline-security-alert-3](Parsers/parserContent_lastline-security-alert-3.md)<br> ↳ [lastline-security-alert-2](Parsers/parserContent_lastline-security-alert-2.md)<br> ↳ [lastline-security-alert-1](Parsers/parserContent_lastline-security-alert-1.md)<br> ↳ [auth0-password-breached](Parsers/parserContent_auth0-password-breached.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                                                                                 | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_johnson_controls_johnson_controls_p2000_Ransomware.md)                                                   |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                                                                                                                                                                                                                       | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Credential Access                                                | Discovery | Lateral Movement                                                                                                                                                                                                                                                                                                                                    | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Command and Scripting Interperter](https://attack.mitre.org/techniques/T1059)<br><br>[User Execution](https://attack.mitre.org/techniques/T1204)<br><br>[Command and Scripting Interperter: PowerShell](https://attack.mitre.org/techniques/T1059/001)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Obfuscated Files or Information: Indicator Removal from Tools](https://attack.mitre.org/techniques/T1027/005)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Use Alternate Authentication Material: Pass the Hash](https://attack.mitre.org/techniques/T1550/002)<br><br>[Use Alternate Authentication Material: Web Session Cookie](https://attack.mitre.org/techniques/T1550/004)<br><br>[Use Alternate Authentication Material: Pass the Ticket](https://attack.mitre.org/techniques/T1550/003)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br> | [Brute Force](https://attack.mitre.org/techniques/T1110)<br><br> |           | [Exploitation of Remote Services](https://attack.mitre.org/techniques/T1210)<br><br>[Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Remote Services: Remote Desktop Protocol](https://attack.mitre.org/techniques/T1021/001)<br><br> |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |