Vendor: AlgoSec
===============
Product: Firewall Analyzer
--------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   9   |   6    |     2      |      1      |    1    |

|                                  Use-Case                                  | Event Types/Parsers                                                                                      | MITRE TTP                                                                     | Content                                                                                                                      |
|:--------------------------------------------------------------------------:| -------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  network-alert<br> ↳ [cef-algosec-network-alert](Parsers/parserContent_cef-algosec-network-alert.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br> | [<ul><li>5 Rules</li></ul><ul><li>4 Models</li></ul>](Rules_Models/r_m_algosec_firewall_analyzer_Compromised_Credentials.md) |
|                 [Malware](../../../UseCases/uc_malware.md)                 |  network-alert<br> ↳ [cef-algosec-network-alert](Parsers/parserContent_cef-algosec-network-alert.md)<br> | T1204 - User Execution<br>                                                    | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_algosec_firewall_analyzer_Malware.md)                 |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution                                                           | Persistence | Privilege Escalation | Defense Evasion                                                                                                                                                                                            | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| -------------- | ------------------------------------------------------------------- | ----------- | -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
|                | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> |             |                      | [Obfuscated Files or Information: Indicator Removal from Tools](https://attack.mitre.org/techniques/T1027/005)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br> |                   |           |                  |            |                     |              |        |