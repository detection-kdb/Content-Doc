Vendor: SecureNet
=================
Product: SecureNet
------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  26   |   7    |     8      |      2      |    2    |

|                Use-Case                | Activity Types                                                                                                                                                                                                                                              | Event Types/Parsers                                                                                                                                               | MITRE TTP                                                                                                                                                                                                                                               | Content                                                                                               |
|:--------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Credential Switch Activity</li><li>Data Loss Prevention</li><li>Email Activity</li><li>Network zones and Location Access</li><li>VPN Activity</li></ul> |  vpn-login<br> ↳ [ipsec-vpn-user](Parsers/parserContent_ipsec-vpn-user.md)<br><br> vpn-logout<br> ↳ [ipsec-vpn-user](Parsers/parserContent_ipsec-vpn-user.md)<br> | T1003 - OS Credential Dumping<br>T1048 - Exfiltration Over Alternative Protocol<br>T1052 - Exfiltration Over Physical Medium<br>T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>T1188 - T1188<br>T1208 - T1208<br> | [<ul><li>26 Rules</li></ul><ul><li>7 Models</li></ul>](Rules_Models/r_m_securenet_securenet_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access                                                                                                                          | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                                                                                                      | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ---------------- | ---------- | ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br>[Brute Force](https://attack.mitre.org/techniques/T1110)<br><br> |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Physical Medium](https://attack.mitre.org/techniques/T1052)<br><br> |        |