#### Parser Content
```Java
{
Name = json-zeek_ssl
  Product = Zeek Network Security Monitor
  DataType = "authentication-successful"
  Conditions = [ """ zeek_ssl """, """"id.orig_h""", """"id.resp_h""" ]
  Fields = ${BroParserTemplates.json-zeek-activity.Fields}[
    """"version\\?"{1,20}:\\?"{1,20}({service}[^"\\]+)""",
    """"cipher\\?"{1,20}:\\?"{1,20}({auth_method}[^"\\]+)"""
    """"established\\?"{1,20}:({outcome}\w+)""",
    """"validation_status"{1,20}:"{1,20}({failure_reason}[^"]+)""",
  ]
}
json-zeek-activity = {
  Vendor = Zeek
  Product = Zeek Network Security Monitor
  Lms = Splunk
  TimeFormat = "epoch"
  Fields = [
    """exabeam_host=([^@=]+@\s{0,100})?({host}\S+)""",
    """"ts"{1,20}:({time}\d{1,100})""",
    """"uid\\?"{1,20}:\\?"{1,20}({conn_id}[^"\\]+)""",
    """"id\.orig_h\\?"{1,20}:\\?"{1,20}({src_ip}[a-fA-F\d.:]+)""",
    """"id\.orig_p\\?"{1,20}:({src_port}\d{1,100})""",
    """"id\.resp_h\\?"{1,20}:\\?"{1,20}({dest_ip}[a-fA-F\d.:]+)""",
    """"id\.resp_p\\?"{1,20}:({dest_port}[a-fA-F\d.:]+)""",
  ]

```