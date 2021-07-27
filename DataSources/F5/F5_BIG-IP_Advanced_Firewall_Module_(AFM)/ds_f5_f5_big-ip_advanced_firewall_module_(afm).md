Vendor: F5
==========
Product: F5 BIG-IP Advanced Firewall Module (AFM)
-------------------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  39   |   17   |     5      |      2      |    2    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  network-connection-failed<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br><br> network-connection-successful<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br> | T1046 - Network Service Scanning<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_f5_f5_big-ip_advanced_firewall_module_(afm)_Compromised_Credentials.md) |
|    [Cryptomining](../../../UseCases/uc_cryptomining.md)    |  network-connection-failed<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br><br> network-connection-successful<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br> | T1496 - Resource Hijacking<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_f5_f5_big-ip_advanced_firewall_module_(afm)_Cryptomining.md)    |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  network-connection-failed<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br><br> network-connection-successful<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br> | T1046 - Network Service Scanning<br>T1071 - Application Layer Protocol<br>T1090.002 - Proxy: External Proxy<br>T1571 - Non-Standard Port<br> | [<ul><li>35 Rules</li></ul><ul><li>17 Models</li></ul>](RM/r_m_f5_f5_big-ip_advanced_firewall_module_(afm)_Lateral_Movement.md)      |
|    [Malware](../../../UseCases/uc_malware.md)    |  network-connection-failed<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br><br> network-connection-successful<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br> | T1071 - Application Layer Protocol<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_f5_f5_big-ip_advanced_firewall_module_(afm)_Malware.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  network-connection-failed<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br><br> network-connection-successful<br> ↳[f5-network-connection](Ps/pC_f5networkconnection.md)<br> | T1071 - Application Layer Protocol<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_f5_f5_big-ip_advanced_firewall_module_(afm)_Ransomware.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery                                                                     | Lateral Movement | Collection | Command and Control                                                                                                                                                                                                                                                                           | Exfiltration | Impact                                                                  |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | ----------------------------------------------------------------------------- | ---------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------- |
|                |           |             |                      |                 |                   | [Network Service Scanning](https://attack.mitre.org/techniques/T1046)<br><br> |                  |            | [Non-Standard Port](https://attack.mitre.org/techniques/T1571)<br><br>[Proxy: External Proxy](https://attack.mitre.org/techniques/T1090/002)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              | [Resource Hijacking](https://attack.mitre.org/techniques/T1496)<br><br> |