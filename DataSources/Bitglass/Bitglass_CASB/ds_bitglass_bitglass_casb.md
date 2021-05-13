Vendor: Bitglass
================
Product: Bitglass CASB
----------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  99   |   46   |     12     |      6      |    6    |

|                                           Use-Case                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | MITRE TTP                                                                                                                                                                                                                      | Content                                                                                                                              |
|:--------------------------------------------------------------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                                                                                                                 | [<ul><li>18 Rules</li></ul><ul><li>11 Models</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Abnormal_Authentication_&_Access.md) |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1003.003 - T1003.003<br>T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1133 - External Remote Services<br>                                                                                                | [<ul><li>16 Rules</li></ul><ul><li>8 Models</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Compromised_Credentials.md)           |
|                      [Data Access](../../../UseCases/uc_data_access.md)                      |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>                                                                                                                                                             | [<ul><li>8 Rules</li></ul><ul><li>7 Models</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Data_Access.md)                        |
|                [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)                |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1020 - Automated Exfiltration<br>T1048 - Exfiltration Over Alternative Protocol<br>T1204 - User Execution<br>                                                                                                                 | [<ul><li>17 Rules</li></ul><ul><li>10 Models</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Data_Exfiltration.md)                |
|                        [Data Leak](../../../UseCases/uc_data_leak.md)                        |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1020 - Automated Exfiltration<br>T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1204 - User Execution<br> | [<ul><li>44 Rules</li></ul><ul><li>23 Models</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Data_Leak.md)                        |
|                          [Evasion](../../../UseCases/uc_evasion.md)                          |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>                                                                                                                                                                                         | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Evasion.md)                                                      |
|                          [Malware](../../../UseCases/uc_malware.md)                          |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1003.002 - T1003.002<br>T1027 - Obfuscated Files or Information<br>T1078 - Valid Accounts<br>T1085 - Signed Binary Proxy Execution: Rundll32<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>              | [<ul><li>10 Rules</li></ul><ul><li>3 Models</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Malware.md)                           |
|                         [Phishing](../../../UseCases/uc_phishing.md)                         |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>                                                             | [<ul><li>14 Rules</li></ul><ul><li>7 Models</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Phishing.md)                          |
|                  [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)                  |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                     | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Privilege_Abuse.md)                                              |
|              [Privileged Activity](../../../UseCases/uc_privileged_activity.md)              |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                     | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Privileged_Activity.md)                                          |
|                       [Ransomware](../../../UseCases/uc_ransomware.md)                       |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                     | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Ransomware.md)                                                   |
|             [Workforce Protection](../../../UseCases/uc_workforce_protection.md)             |  app-login<br> ↳ [bitglass-app-login](Parsers/parserContent_bitglass-app-login.md)<br><br> dlp-alert<br> ↳ [cef-bitglass-dlp-alert](Parsers/parserContent_cef-bitglass-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [bitglass-dlp-email-alert-out](Parsers/parserContent_bitglass-dlp-email-alert-out.md)<br><br> failed-app-login<br> ↳ [bitglass-app-login-failed](Parsers/parserContent_bitglass-app-login-failed.md)<br><br> file-read<br> ↳ [bitglass-file-read](Parsers/parserContent_bitglass-file-read.md)<br><br> file-write<br> ↳ [bitglass-file-write](Parsers/parserContent_bitglass-file-write.md)<br> | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>                                                                                                               | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_bitglass_bitglass_casb_Workforce_Protection.md)               |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                                                                                                                                                                                                     | Credential Access                                                          | Discovery                                                                         | Lateral Movement | Collection | Command and Control                                                                                                                       | Exfiltration                                                                                                                                                                                                                                                                                                                    | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ---------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Signed Binary Proxy Execution: Rundll32](https://attack.mitre.org/techniques/T1085)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br>[Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> |        |