#### Parser Content
```Java
{
Name = raw-unix-password-change
  Vendor = Unix
  Product = Unix
  Lms = Direct
  DataType = "password-change"
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [ """pam_unix(passwd:chauthtok):""", "password changed for" ]
  Fields = [
    """exabeam_time=({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
    """exabeam_host=(gcs-topic|({host}[\w.\-]{1,2000}))""",
    """"agent_hostname":"({host}[^"]{1,200})"""",
    """\d\d:\d\d:\d\d ({host}[\w.\-]{1,2000})""",
    """password changed for ({target_user}.+?)\s{0,20}("|$)""",
  ]
  DupFields = [ "host->dest_host" ]
}
```