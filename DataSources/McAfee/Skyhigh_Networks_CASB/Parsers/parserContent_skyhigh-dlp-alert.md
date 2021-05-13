#### Parser Content
```Java
{
Name = skyhigh-dlp-alert
  Vendor = McAfee
  Product = Skyhigh Networks CASB
  Lms = Splunk
  DataType = "dlp-alert"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
  Conditions = [ "anomaly.timeupdated=",",activityName=", ",MimeType="]
  Fields = [
            """\d{1,100}:\d{1,100}:\d{1,100}\s({host}[^\s]+)\s\w+=""",
            """,timestamp=({time}\d\d\d\d\-\d\d\-\d\dT\d{1,100}:\d{1,100}:\d{1,100})""",
            """\sriskLevel=({alert_severity}[^,]+)""",
            """,userAction=({alert_name}[^,]+)""",
            """,destinationHost=({dest_host}[^,]+)""",
            """,userDisplayName=({user}[^,]+)""",
            """,ByteCount=({bytes}[^,]+)""",
            """,MimeType=({additional_info}[^,]+)""",
            """,response=({outcome}[^,]+)""",
           ]
    DupFields = [ "alert_name->alert_type" ]
}
```