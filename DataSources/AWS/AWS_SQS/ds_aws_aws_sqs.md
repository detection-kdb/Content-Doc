Vendor: AWS
===========
Product: AWS SQS
----------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  60   |   30   |     6      |      5      |    5    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                            | MITRE TTP                                                                                                                                                                                           | Content                                                                                        |
|:--------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  app-activity<br> ↳ [s-aws-app-activity](Parsers/parserContent_s-aws-app-activity.md)<br><br> app-activity-failed<br> ↳ [s-aws-app-activity](Parsers/parserContent_s-aws-app-activity.md)<br><br> file-delete<br> ↳ [s-aws-app-activity](Parsers/parserContent_s-aws-app-activity.md)<br><br> file-read<br> ↳ [s-aws-app-activity](Parsers/parserContent_s-aws-app-activity.md)<br><br> file-write<br> ↳ [s-aws-app-activity](Parsers/parserContent_s-aws-app-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1133 - External Remote Services<br>T1188 - T1188<br>T1204 - User Execution<br> | [<ul><li>60 Rules</li></ul><ul><li>30 Models</li></ul>](Rules_Models/r_m_aws_aws_sqs_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery                                                                         | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------------------------------------------------------------------------------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |