#### Parser Content
```Java
{
Name = wazuh-4776
  DataType = "windows-4776"
  Conditions = [ """"data.id":"4776"""", """"type":"wazuh-alerts"""", """"decoder.parent":"windows""""  ]
  Fields = ${WazuhParserTemplates.wazuh-windows-template.Fields} [
    """({event_name}The (computer|domain controller) attempted to validate the credentials for an account)"""
      """The ({login_type}computer|domain)(\s\w+)? attempted to validate the credentials"""
      """Logon (?:a|A)ccount:(?:\s{1,100}Source Workstation|\s{0,100}({user}[^\s@]+?)(?:@({domain}[^\s.]+).*?)?\s{0,100}Source Workstation)"""
      """Error Code:\s{0,100}({result_code}[\w\-]+)"""
      """Source Workstation:\s{0,100}\\*(?:\s{1,100}Error Code:|(({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})\s{0,100}Error Code:)|(\s{0,100}({dest_host}[^\s]+?)\s{0,100}Error Code:))\s{0,100}""" 
  ]
}
wazuh-windows-template = {
    Vendor = Microsoft
    Product = Microsoft Windows
    Lms = Direct
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
    Fields = [
      """"data.id":"({event_code}\d{1,100})""""
      """"@timestamp":"({time}\d{4}-\d\d-\d\dT\d\d:\d\d:\d\d\.\d\d\dZ)"""
      """"data.dstuser":"(\(no user\)|({dest_user}[^"]+))"""
      """"data.status":"({outcome}[^"]+)"""
      """"location":"({log_location}[^"]+)"""
      """"data.data":"({data}[^"]+)"""
      """"path":"({log_path}[^"]+)"""
      """"data.system_name":"({host}[^"]+)"""
      """"agent.id":"({agent_id}\d{1,100})"""
      """"manager.name":"({wazuh_manager}[^"]+)"""
      """"data.data":"({data}[^"]+)"""
      """"rule.description":"({description}[^"]+)"""
      """"decoder.name":"({decoder_name}[^"]+)"""
    ]

```