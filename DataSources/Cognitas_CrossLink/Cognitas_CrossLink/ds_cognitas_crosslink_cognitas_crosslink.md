Vendor: Cognitas CrossLink
==========================
Product: Cognitas CrossLink
---------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  12   |   5    |     3      |      1      |    1    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  vpn-login<br> ↳[cognitas-vpn-start](Ps/pC_cognitasvpnstart.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | [<ul><li>6 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_cognitas_crosslink_cognitas_crosslink_Abnormal_Authentication_&_Access.md) |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  vpn-login<br> ↳[cognitas-vpn-start](Ps/pC_cognitasvpnstart.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_cognitas_crosslink_cognitas_crosslink_Compromised_Credentials.md)          |
|    [Evasion](../../../UseCases/uc_evasion.md)    |  vpn-login<br> ↳[cognitas-vpn-start](Ps/pC_cognitasvpnstart.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_cognitas_crosslink_cognitas_crosslink_Evasion.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  vpn-login<br> ↳[cognitas-vpn-start](Ps/pC_cognitasvpnstart.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_cognitas_crosslink_cognitas_crosslink_Malware.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  vpn-login<br> ↳[cognitas-vpn-start](Ps/pC_cognitasvpnstart.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_cognitas_crosslink_cognitas_crosslink_Ransomware.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |