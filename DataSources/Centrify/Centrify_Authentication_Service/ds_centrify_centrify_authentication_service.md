Vendor: Centrify
================
Product: Centrify Authentication Service
----------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  78   |   32   |     17     |      6      |    6    |

|                                           Use-Case                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | MITRE TTP                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Content                                                                                                                                                |
|:--------------------------------------------------------------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1021 - Remote Services<br>T1078 - Valid Accounts<br>T1078.003 - Valid Accounts: Local Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>                                                                                                                                                                                                                                                                                                                                                             | [<ul><li>28 Rules</li></ul><ul><li>15 Models</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Abnormal_Authentication_&_Access.md) |
|               [Brute Force Attack](../../../UseCases/uc_brute_force_attack.md)               |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1021.001 - Remote Services: Remote Desktop Protocol<br>T1078 - Valid Accounts<br>T1110 - Brute Force<br>                                                                                                                                                                                                                                                                                                                                                                                                                  | [<ul><li>6 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Brute_Force_Attack.md)                 |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                             | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Compromised_Credentials.md)            |
|                          [Evasion](../../../UseCases/uc_evasion.md)                          |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Evasion.md)                                                      |
|                 [Lateral Movement](../../../UseCases/uc_lateral_movement.md)                 |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1018 - Remote System Discovery<br>T1021 - Remote Services<br>T1021.001 - Remote Services: Remote Desktop Protocol<br>T1075 - T1075<br>T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1550 - Use Alternate Authentication Material<br>T1550.002 - Use Alternate Authentication Material: Pass the Hash<br>T1550.003 - Use Alternate Authentication Material: Pass the Ticket<br>T1550.004 - Use Alternate Authentication Material: Web Session Cookie<br>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting<br> | [<ul><li>32 Rules</li></ul><ul><li>12 Models</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Lateral_Movement.md)                 |
|                          [Malware](../../../UseCases/uc_malware.md)                          |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>T1210 - Exploitation of Remote Services<br>                                                                                                                                                                                                                                                                                                                                                                                      | [<ul><li>6 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Malware.md)                            |
|                  [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)                  |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | [<ul><li>5 Rules</li></ul><ul><li>3 Models</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Privilege_Abuse.md)                    |
|             [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)             |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1078 - Valid Accounts<br>T1210 - Exploitation of Remote Services<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                      | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Privilege_Escalation.md)               |
|              [Privileged Activity](../../../UseCases/uc_privileged_activity.md)              |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Privileged_Activity.md)                |
|                       [Ransomware](../../../UseCases/uc_ransomware.md)                       |  account-password-reset<br> ↳ [centrify-account-password-change-failed-1](Parsers/parserContent_centrify-account-password-change-failed-1.md)<br><br> authentication-failed<br> ↳ [centrify-authentication-failed-1](Parsers/parserContent_centrify-authentication-failed-1.md)<br> ↳ [centrify-authentication-failed-2](Parsers/parserContent_centrify-authentication-failed-2.md)<br><br> authentication-successful<br> ↳ [centrify-authentication-success-1](Parsers/parserContent_centrify-authentication-success-1.md)<br> ↳ [centrify-auth-success](Parsers/parserContent_centrify-auth-success.md)<br><br> failed-logon<br> ↳ [centrify-auth-denied](Parsers/parserContent_centrify-auth-denied.md)<br> ↳ [centrify-failed-logon-2](Parsers/parserContent_centrify-failed-logon-2.md)<br> ↳ [centrify-failed-logon-1](Parsers/parserContent_centrify-failed-logon-1.md)<br> ↳ [centrify-ssh-login-failed](Parsers/parserContent_centrify-ssh-login-failed.md)<br> ↳ [centrify-failed-logon](Parsers/parserContent_centrify-failed-logon.md)<br><br> local-logon<br> ↳ [centrify-local-logon](Parsers/parserContent_centrify-local-logon.md)<br><br> remote-logon<br> ↳ [centrify-remote-logon-2](Parsers/parserContent_centrify-remote-logon-2.md)<br> ↳ [centrify-remote-logon-1](Parsers/parserContent_centrify-remote-logon-1.md)<br> ↳ [centrify-ssh-login](Parsers/parserContent_centrify-ssh-login.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_centrify_centrify_authentication_service_Ransomware.md)                                                   |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Credential Access                                                                                                                                                                                                                                           | Discovery                                                                    | Lateral Movement                                                                                                                                                                                                                                                                                                                                    | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Use Alternate Authentication Material: Pass the Hash](https://attack.mitre.org/techniques/T1550/002)<br><br>[Use Alternate Authentication Material: Web Session Cookie](https://attack.mitre.org/techniques/T1550/004)<br><br>[Use Alternate Authentication Material: Pass the Ticket](https://attack.mitre.org/techniques/T1550/003)<br><br>[Valid Accounts: Local Accounts](https://attack.mitre.org/techniques/T1078/003)<br><br> | [Brute Force](https://attack.mitre.org/techniques/T1110)<br><br>[Steal or Forge Kerberos Tickets](https://attack.mitre.org/techniques/T1558)<br><br>[Steal or Forge Kerberos Tickets: Kerberoasting](https://attack.mitre.org/techniques/T1558/003)<br><br> | [Remote System Discovery](https://attack.mitre.org/techniques/T1018)<br><br> | [Exploitation of Remote Services](https://attack.mitre.org/techniques/T1210)<br><br>[Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br>[Remote Services: Remote Desktop Protocol](https://attack.mitre.org/techniques/T1021/001)<br><br> |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |