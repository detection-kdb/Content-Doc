#### Parser Content
```Java
{
Name = crowdstrike-file-read-3
    Vendor = CrowdStrike
    Product = Falcon
    Lms = Direct
    DataType = "file-read"
    TimeFormat = "epoch"
    Conditions = [ """"event_simpleName":"RansomwareOpenFile"""", """"timestamp":"""" ]
    Fields = [
      """exabeam_host=([^=]+@\s{0,100})?({host}[\w\-.]+)""",
      """"timestamp":"({time}\d{1,100})""",
      """requestClientApplication=({app}[^=]+?)\s{0,100}\w+=""",
      """"aip":"({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})"""",
      """"event_simpleName":"({event_name}[^"]+)"""",
      """"TargetFileName":"({file_parent}[^"]*[\\\/]+)({file_name}[^\\\/"]+(\.({file_ext}[^\\\/"]+)))"""",
      """"TargetFileName":"({file_path}[^"]+)"""",
      """"FileObject":"({object}[^"]+)"""",
      """"aid":"({aid}[^"]+)""""
    ]
  }
```