#### Parser Content
```Java
{
Name = cef-netskope-alert-compromise
  Vendor = Netskope
  Product = Netskope Security Cloud
  Lms = Direct
  DataType = "alert"
  TimeFormat = "epoch_sec"
  Conditions = [ """CEF:""", """|Skyformation|""", """"alert_type":"Compromised Credential"""", """destinationServiceName=Netskope""", """|security-threat-detected|""", """"type":"breach"""" ]
 Fields = [
    """exabeam_host=([^=]+@\s{0,100})?({host}\S+)""",
    """"timestamp":({time}\d{1,100})""",
    """"user":"(({user_email}[^@"\s]+@[^@"\s]+)|(({domain}[^"@\\\/\s]+)[\\\/]+)?({user}[^"@\\\/\s]+))"""",
    """"_id":"({alert_id}[^"]+)""",
    """"category":"(n\/a|({threat_category}[^"]+))""",
    """"alert_type"{1,20}:"{1,20}({alert_name}[^"]+)""",
    """"hostname":"({src_host}[^"]+)""",
    """security-threat-detected\|({alert_severity}\d{1,100})""",
    """"alert_name":"({additional_info}[^"]+)""",
    """"type":"({alert_type}[^"]+)"""
  ]
}
```