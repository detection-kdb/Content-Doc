#### Parser Content
```Java
{
Name = cef-oracle-db-update
  Vendor = Oracle
  Product = Oracle DB
  Lms = ArcSight
  DataType = "database-update"
  IsHVF = true
  TimeFormat = "epoch"
  Conditions = [ """|Oracle|FGA|""", """|UPDATE|""" ]
  Fields = [
    """exabeam_host=([^=]+@\s{0,100})?({host}\S+)""",
    """\Wrt=({time}\d{1,100})""",
    """\Wshost=({src_host}[\w\-.]+)""",
    """\Wdhost=({dest_host}[\w\-.]+)""",
    """\Wsuser=({user}[^\s]+)""",
    """\Wduser=({db_user}[^\s]+)""",
    """\Wcs3=({database_name}[^\s]+)""",
    """CEF:([^\|]*\|){5}({db_operation}[^\|]+)""",
  ]
  DupFields = [ "db_user->account" ]
}
```