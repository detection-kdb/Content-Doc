Vendor: Oracle
==============
Product: Oracle Access Manager
------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  56   |   25   |     5      |      5      |    5    |

|                                           Use-Case                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | MITRE TTP                                                                                           | Content                                                                                                                                    |
|:--------------------------------------------------------------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                      | [<ul><li>22 Rules</li></ul><ul><li>13 Models</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Abnormal_Authentication_&_Access.md) |
|             [Account Manipulation](../../../UseCases/uc_account_manipulation.md)             |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>                           | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Account_Manipulation.md)               |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                      | [<ul><li>20 Rules</li></ul><ul><li>10 Models</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Compromised_Credentials.md)          |
|                      [Data Access](../../../UseCases/uc_data_access.md)                      |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>                                                                          | [<ul><li>17 Rules</li></ul><ul><li>10 Models</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Data_Access.md)                      |
|                        [Data Leak](../../../UseCases/uc_data_leak.md)                        |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1114.003 - Email Collection: Email Forwarding Rule<br>                                             | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Data_Leak.md)                                                    |
|                          [Evasion](../../../UseCases/uc_evasion.md)                          |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>                                                              | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Evasion.md)                                                      |
|                          [Malware](../../../UseCases/uc_malware.md)                          |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>                                    | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Malware.md)                                                      |
|                  [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)                  |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br> | [<ul><li>7 Rules</li></ul><ul><li>3 Models</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Privilege_Abuse.md)                    |
|             [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)             |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>                           | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Privilege_Escalation.md)               |
|              [Privileged Activity](../../../UseCases/uc_privileged_activity.md)              |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br> | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Privileged_Activity.md)                                          |
|                       [Ransomware](../../../UseCases/uc_ransomware.md)                       |  app-activity<br> ↳ [q-oam-app-activity-5](Parsers/parserContent_q-oam-app-activity-5.md)<br> ↳ [q-oam-app-activity-4](Parsers/parserContent_q-oam-app-activity-4.md)<br> ↳ [q-oam-app-activity-7](Parsers/parserContent_q-oam-app-activity-7.md)<br> ↳ [q-oam-app-activity-6](Parsers/parserContent_q-oam-app-activity-6.md)<br> ↳ [q-oam-app-activity-10](Parsers/parserContent_q-oam-app-activity-10.md)<br> ↳ [q-oam-app-activity-9](Parsers/parserContent_q-oam-app-activity-9.md)<br> ↳ [q-oam-app-activity-11](Parsers/parserContent_q-oam-app-activity-11.md)<br> ↳ [q-oam-app-activity-8](Parsers/parserContent_q-oam-app-activity-8.md)<br> ↳ [q-oam-app-activity-12](Parsers/parserContent_q-oam-app-activity-12.md)<br> ↳ [q-oam-app-activity-3](Parsers/parserContent_q-oam-app-activity-3.md)<br> ↳ [q-oam-app-activity-2](Parsers/parserContent_q-oam-app-activity-2.md)<br><br> app-login<br> ↳ [q-oam-app-login](Parsers/parserContent_q-oam-app-login.md)<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> ↳ [s-oam-app-login-1](Parsers/parserContent_s-oam-app-login-1.md)<br><br> authentication-failed<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> authentication-successful<br> ↳ [q-oam-auth-successful](Parsers/parserContent_q-oam-auth-successful.md)<br> ↳ [oracle-access-manager](Parsers/parserContent_oracle-access-manager.md)<br><br> failed-app-login<br> ↳ [s-oam-app-login](Parsers/parserContent_s-oam-app-login.md)<br> | T1078 - Valid Accounts<br>                                                                          | [<ul><li>2 Rules</li></ul>](Rules_Models/r_m_oracle_oracle_access_manager_Ransomware.md)                                                   |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |