#### Parser Content
```Java
{
Name = racf-db-access-2
  DataType = "database-access"
  Conditions = [ """EVNTPRODESCR=VANGUARD_ACTIVE_ALERTS""", """EVNTNAME=CONNECT""", """EVNTTEXT=Successful""" ]
  Fields = ${IBMracfParserTemplates.ibm-racf-activity.Fields} [
  ]
}
ibm-racf-activity = {
Vendor = IBM
Product = IBM Racf
Lms = Splunk
TimeFormat = "yyyy-MM-dd HH:mm:ss"
Fields = [
  """exabeam_host=([^=]+@\s{0,100})?({host}\S+)""",
  """exabeam_time=({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
  """APPLSIEMVRM=({host}[^=]+?)\s\w+=""",
  """APPLHOSTIPADD=({host_ip}[A-Fa-f.:\d]+)""",
  """EVNTUSERID=({db_user}[^=]+?)\s\w+=""",
  """EVNTNAME=({event_name}[^=]+?)\s\w+=""",
  """EVNTUSERNAME=(\-*N\/A\-*|({user}[^=]+?))\s\w+=""",
  """EVNTTEXT=({additional_info}[^=]+?)\s\w+=""",
  """EVNTCOMMAND=(\-*N\/A\-*|({db_query}[^=]+?))(\s\w+=|\s{0,100}$)""",
  """EVNTCLASSNAME=(\-*N\/A\-*|({database_object}[^=]+?))\s{0,100}\w+="""
  ]

```