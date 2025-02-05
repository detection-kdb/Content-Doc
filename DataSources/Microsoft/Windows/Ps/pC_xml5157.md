#### Parser Content
```Java
{
Name = xml-5157
  Vendor = Microsoft
  Product = Windows
  Lms = Exabeam
  DataType = "process-network-failed"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSS"
  Conditions = [ """<EventID>5157</EventID>""", """<Event xmlns""" ]
  Fields = [
    """({event_name}The Windows Filtering Platform has blocked a connection)""",
    """<TimeCreated SystemTime(\\)?='({time}\d{4}-\d\d-\d\dT\d\d:\d\d:\d\d\.\d\d\d)\d{1,100}Z'/>""",
    """<EventID>({event_code}5157)<""",
    """<Computer>({host}[^<>]{1,2000})</Computer>""",
    """<Data Name(\\)?='ProcessID'>({pid}[^<>]{1,2000})<\/Data>""",
    """<Data Name(\\)?='Application'>({process}({process_directory}(?:[^<]{1,2000})?[\\\/])?({process_name}[^\\\/]{1,2000}?))<\/Data>""",
    """<Data Name(\\)?='SourceAddress'>({src_ip}[a-fA-F:\d.]{1,2000})</Data>""",
    """<Data Name(\\)?='SourcePort'>({src_port}\d{1,100})</Data>""",
    """<Data Name(\\)?='DestAddress'>({dest_ip}[a-fA-F:\d.]{1,2000})</Data>""",
    """<Data Name(\\)?='DestPort'>({dest_port}\d{1,100})</Data>""",
    """<Data Name(\\)?='Protocol'>({protocol}[^<>]{1,2000})</Data>""",
    """<RenderingInfo.+?<Task>({activity_type}[^<>]{1,2000})</Task>.*?</RenderingInfo>""",
    """<Computer>({src_host}[^<>]{1,2000})</Computer>.+?Direction:\s{0,100}({direction}Outbound)""",
    """<Computer>({dest_host}[^<>]{1,2000})</Computer>.+?Direction:\s{0,100}({direction}Inbound)""",
    """<Data Name(\\)?='LayerName'>({layer_name}[^<]{1,2000})"""
  ]
  DupFields = [ "host->local_asset" ]
}
```