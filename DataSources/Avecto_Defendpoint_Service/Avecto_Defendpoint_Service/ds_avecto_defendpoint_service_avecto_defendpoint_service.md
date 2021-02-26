Vendor: Avecto Defendpoint Service
==================================
Product: Avecto Defendpoint Service
-----------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  43   |   6    |     5      |      1      |    1    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                      | MITRE TTP                                                                                                                                               | Content                                                                                                                                 |
|:--------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  process-created<br> ↳ [avecto-process-created](Parsers/parserContent_avecto-process-created.md)<br> ↳ [avecto-process-created-1](Parsers/parserContent_avecto-process-created-1.md)<br> | T1016 - System Network Configuration Discovery<br>T1036 - Masquerading<br>T1086 - T1086<br>T1204 - User Execution<br>T1219 - Remote Access Software<br> | [<ul><li>43 Rules</li></ul><ul><li>6 Models</li></ul>](Rules_Models/r_m_avecto_defendpoint_service_avecto_defendpoint_service_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution                                                           | Persistence | Privilege Escalation | Defense Evasion                                                   | Credential Access | Discovery                                                                                   | Lateral Movement | Collection | Command and Control                                                         | Exfiltration | Impact |
| -------------- | ------------------------------------------------------------------- | ----------- | -------------------- | ----------------------------------------------------------------- | ----------------- | ------------------------------------------------------------------------------------------- | ---------------- | ---------- | --------------------------------------------------------------------------- | ------------ | ------ |
|                | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> |             |                      | [Masquerading](https://attack.mitre.org/techniques/T1036)<br><br> |                   | [System Network Configuration Discovery](https://attack.mitre.org/techniques/T1016)<br><br> |                  |            | [Remote Access Software](https://attack.mitre.org/techniques/T1219)<br><br> |              |        |