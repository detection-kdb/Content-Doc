Vendor: IBM
===========
### Product: [IBM Lotus Notes](../ds_ibm_ibm_lotus_notes.md)
### Use-Case: [Other](../../../../UseCases/uc_other.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  17   |   13   |     2      |      2      |    2    |

| Event Type                    | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| network-connection-successful | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>NET-ZCountry-Inbound-A</b>: Abnormal connection from this country for the zone<br> ↳ <b>NET-OCountry-Inbound-F</b>: First inbound connection from this country for organization<br> ↳ <b>NET-ZCountry-Outbound-A</b>: Abnormal outbound connection country for the zone<br> ↳ <b>NET-OCountry-Outbound-F</b>: First outbound connection to this country from organization<br> ↳ <b>NET-TI-H-Outbound</b>: Outbound connection to a known malicious host<br> ↳ <b>NET-ZsH-Outbound-A</b>: Abnormal outbound connection for asset for zone<br> ↳ <b>NET-HsH-Outbound-F</b>: First outbound connection for asset<br> ↳ <b>NET-OsZ-Outbound-F</b>: First outbound connection from zone for organization<br> ↳ <b>NET-ZsZ-Outbound-A</b>: Abnormal outbound connection from zone for asset<br> ↳ <b>NET-HsZ-Outbound-F</b>: First outbound connection from zone for asset<br> ↳ <b>NET-HsZ-Outbound-A</b>: Abnormal outbound connection from zone<br> ↳ <b>NET-ZdH-Inbound-A</b>: Abnormal inbound connection to host for the zone.<br> ↳ <b>A-NET-Ransomware-IP</b>: Asset attempted to connect to an IP address which is associated to Ransomware<br><br><b>T1065 - T1065</b><br> ↳ <b>NET-HdPort-Outbound-F</b>: First outbound connection on port for asset<br> ↳ <b>NET-HdPort-Outbound-A</b>: Abnormal outbound connection to destination port for the asset.<br> ↳ <b>NET-ZdPort-Outbound-F</b>: First outbound connection on port for zone<br> ↳ <b>NET-OdPort-Outbound-A</b>: Abnormal outbound traffic to port for the organization. |  • <b>A-NET-ZdH-Inbound</b>: Hosts receiving inbound communications in the zone<br> • <b>A-NET-HsZ-Outbound</b>: Outbound communicating zones for the asset<br> • <b>A-NET-ZsZ-Outbound</b>: Outbound communicating zones<br> • <b>A-NET-OsZ-Outbound</b>: Outbound communicating zones in the organization<br> • <b>A-NET-HsH-Outbound</b>: Outbound communicating hosts for the asset<br> • <b>A-NET-ZsH-Outbound</b>: Outbound communicating hosts in the zone<br> • <b>A-NET-OdPort-Outbound</b>: Outbound destination ports per organization<br> • <b>A-NET-OCountry-Outbound</b>: Outbound country per organization<br> • <b>A-NET-ZCountry-Outbound</b>: Outbound country per zone<br> • <b>A-NET-OCountry-Inbound</b>: Origination country per organization<br> • <b>A-NET-ZCountry-Inbound</b>: Origination country per zone<br> • <b>A-NET-ZdPort-Outbound</b>: Outbound destination ports per zone<br> • <b>A-NET-HdPort-Outbound</b>: Outbound destination ports per asset |