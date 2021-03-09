Vendor: Check Point Software
============================
Product: Check Point Identity Awareness
---------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  22   |   3    |     10     |      1      |    1    |

|                                 Use-Case                                  | Activity Types                                                                                                                                              | Event Types/Parsers                                                                                                                                                                                                                                                        | MITRE TTP                                                                                                                                                                                                                                                                                                                                                    | Content                                              |
|:-------------------------------------------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | <ul><li>Application Activity</li><li>Asset Logon and Access</li><li>Credential Switch Activity</li><li>Email Activity</li><li>Privileged Activity</li></ul> |  vpn-logout<br> ↳ [checkpoint-vpn-logout-1](../Parsers/parserContent_checkpoint-vpn-logout-1.md)<br> ↳ [checkpoint-vpn-logout](../Parsers/parserContent_checkpoint-vpn-logout.md)<br> ↳ [checkpoint-vpn-logout-2](../Parsers/parserContent_checkpoint-vpn-logout-2.md)<br> | T1003 - OS Credential Dumping<br>T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1110 - Brute Force<br>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting<br>                                                                                                    | <ul><li>12 Rules</li></ul><ul><li>3 Models</li></ul> |
|       [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)       | <ul><li>Application Activity</li><li>Data Loss Prevention</li><li>Email Activity</li></ul>                                                                  |  vpn-logout<br> ↳ [checkpoint-vpn-logout-1](../Parsers/parserContent_checkpoint-vpn-logout-1.md)<br> ↳ [checkpoint-vpn-logout](../Parsers/parserContent_checkpoint-vpn-logout.md)<br> ↳ [checkpoint-vpn-logout-2](../Parsers/parserContent_checkpoint-vpn-logout-2.md)<br> | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1052 - Exfiltration Over Physical Medium<br>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB<br>T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1566 - Phishing<br> | <ul><li>8 Rules</li></ul>                            |
|          [Internal Fraud](../UseCases/usecase_internal_fraud.md)          | <ul><li>Application Activity</li></ul>                                                                                                                      |  vpn-logout<br> ↳ [checkpoint-vpn-logout-1](../Parsers/parserContent_checkpoint-vpn-logout-1.md)<br> ↳ [checkpoint-vpn-logout](../Parsers/parserContent_checkpoint-vpn-logout.md)<br> ↳ [checkpoint-vpn-logout-2](../Parsers/parserContent_checkpoint-vpn-logout-2.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                   | <ul><li>1 Rules</li></ul>                            |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | <ul><li>Asset Logon and Access</li></ul>                                                                                                                    |  vpn-logout<br> ↳ [checkpoint-vpn-logout-1](../Parsers/parserContent_checkpoint-vpn-logout-1.md)<br> ↳ [checkpoint-vpn-logout](../Parsers/parserContent_checkpoint-vpn-logout.md)<br> ↳ [checkpoint-vpn-logout-2](../Parsers/parserContent_checkpoint-vpn-logout-2.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                                                                                                                                                   | <ul><li>1 Rules</li></ul>                            |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | <ul><li>Email Activity</li></ul>                                                                                                                            |  vpn-logout<br> ↳ [checkpoint-vpn-logout-1](../Parsers/parserContent_checkpoint-vpn-logout-1.md)<br> ↳ [checkpoint-vpn-logout](../Parsers/parserContent_checkpoint-vpn-logout.md)<br> ↳ [checkpoint-vpn-logout-2](../Parsers/parserContent_checkpoint-vpn-logout-2.md)<br> | T1566 - Phishing<br>                                                                                                                                                                                                                                                                                                                                         | <ul><li>1 Rules</li></ul>                            |
|                [Phishing](../UseCases/usecase_phishing.md)                | <ul><li>Email Activity</li></ul>                                                                                                                            |  vpn-logout<br> ↳ [checkpoint-vpn-logout-1](../Parsers/parserContent_checkpoint-vpn-logout-1.md)<br> ↳ [checkpoint-vpn-logout](../Parsers/parserContent_checkpoint-vpn-logout.md)<br> ↳ [checkpoint-vpn-logout-2](../Parsers/parserContent_checkpoint-vpn-logout-2.md)<br> | T1566 - Phishing<br>                                                                                                                                                                                                                                                                                                                                         | <ul><li>1 Rules</li></ul>                            |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | <ul><li>Application Activity</li><li>Credential Switch Activity</li><li>Privileged Activity</li></ul>                                                       |  vpn-logout<br> ↳ [checkpoint-vpn-logout-1](../Parsers/parserContent_checkpoint-vpn-logout-1.md)<br> ↳ [checkpoint-vpn-logout](../Parsers/parserContent_checkpoint-vpn-logout.md)<br> ↳ [checkpoint-vpn-logout-2](../Parsers/parserContent_checkpoint-vpn-logout-2.md)<br> | T1003 - OS Credential Dumping<br>T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>                                                                                                                                                                                                                                                                  | <ul><li>6 Rules</li></ul><ul><li>1 Models</li></ul>  |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | <ul><li>Email Activity</li></ul>                                                                                                                            |  vpn-logout<br> ↳ [checkpoint-vpn-logout-1](../Parsers/parserContent_checkpoint-vpn-logout-1.md)<br> ↳ [checkpoint-vpn-logout](../Parsers/parserContent_checkpoint-vpn-logout.md)<br> ↳ [checkpoint-vpn-logout-2](../Parsers/parserContent_checkpoint-vpn-logout-2.md)<br> | T1566 - Phishing<br>                                                                                                                                                                                                                                                                                                                                         | <ul><li>1 Rules</li></ul>                            |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                   | Execution | Persistence                                                                                                                                                                                                                                                    | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access                                                                                                                                                                                                                                                                                                                     | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                                                                                                                                                                                                                                                                                                                                                                                | Impact |
| -------------------------------------------------------------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ---------------- | ---------- | ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Phishing](https://attack.mitre.org/techniques/T1566)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br>[Brute Force](https://attack.mitre.org/techniques/T1110)<br><br>[Steal or Forge Kerberos Tickets](https://attack.mitre.org/techniques/T1558)<br><br>[Steal or Forge Kerberos Tickets: Kerberoasting](https://attack.mitre.org/techniques/T1558/003)<br><br> |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br>[Exfiltration Over Physical Medium: Exfiltration over USB](https://attack.mitre.org/techniques/T1052/001)<br><br>[Exfiltration Over Physical Medium](https://attack.mitre.org/techniques/T1052)<br><br> |        |