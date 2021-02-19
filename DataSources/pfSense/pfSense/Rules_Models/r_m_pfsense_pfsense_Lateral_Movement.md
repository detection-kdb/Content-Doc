Vendor: pfSense
===============
### Product: [pfSense](../ds_pfsense_pfsense.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  11   |   1    |     3      |      1      |    1    |

| Event Type                | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Models |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| network-connection-failed | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>NETF-OsH-Outbound-F</b>: First failed outbound connection for host in the organization<br> ↳ <b>NETF-HsH-Outbound-F</b>: First failed outbound connection for host<br> ↳ <b>NETF-HsH-Outbound-A</b>: Abnormal outbound connection from host failed<br> ↳ <b>NETF-OsZ-Outbound-F</b>: First failed outbound connection from zone<br> ↳ <b>A-NETF-Ransomware-IP</b>: Asset failed to connect to an IP address which is associated to Ransomware<br><br><b>T1090.002 - Proxy: External Proxy</b><br> ↳ <b>NETF-ZCountry-Outbound-F</b>: First failed outbound connection to this country from zone<br> ↳ <b>NETF-ZsH-Outbound-A</b>: Abnormal outbound connection from host failed in the zone<br><br><b>T1571 - Non-Standard Port</b><br> ↳ <b>NETF-HdPort-Outbound-F</b>: First failed outbound connection on port for asset<br> ↳ <b>NETF-HdPort-Outbound-A</b>: Outbound connection to abnormal port for asset has failed<br> ↳ <b>NETF-OdPort-Outbound-F</b>: First outbound traffic to previously unused port for the organization failed<br> ↳ <b>NETF-OdPort-Outbound-A</b>: Outbound traffic to abnormal port for the organization failed |        |