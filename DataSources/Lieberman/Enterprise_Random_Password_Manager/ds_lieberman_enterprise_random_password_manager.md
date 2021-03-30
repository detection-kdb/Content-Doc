Vendor: Lieberman
=================
Product: Enterprise Random Password Manager
-------------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   5   |   3    |     2      |      1      |    1    |

|                Use-Case                | Event Types/Parsers                                                                    | MITRE TTP                                            | Content                                                                                                                       |
|:--------------------------------------:| -------------------------------------------------------------------------------------- | ---------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  privileged-access<br> ↳ [lieberman-erpm](Parsers/parserContent_lieberman-erpm.md)<br> | T1078 - Valid Accounts<br>T1204 - User Execution<br> | [<ul><li>5 Rules</li></ul><ul><li>3 Models</li></ul>](Rules_Models/r_m_lieberman_enterprise_random_password_manager_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     |              |        |