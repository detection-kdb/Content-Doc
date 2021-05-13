#### Parser Content
```Java
{
Name = juniper-commit-events
  Vendor = Juniper Networks
  Product = Juniper Networks
  Lms = Direct
  DataType = "config-change"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Conditions = [ """ mgd """, """ UI_COMMIT """, """ requested """ ]
  Fields = [
    """<\d{1,100}>\d{1,100}\s{1,100}({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d\d\d(\+|\-)\d\d:\d\d)""",
    """({host}\S+)\s{1,100}mgd\s""",
    """\sUser '({user}[^']+)' requested '({activity}[^']+)' """
  ]
  DupFields = [ "host->dest_host" ]
}
```