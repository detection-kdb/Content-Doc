#### Parser Content
```Java
{
Name = cef-mbmc-security-alert-detection-1
    Conditions = [ """CEF:""", """|Malwarebytes|Malwarebytes""", """|Detection|""" ]
    Fields = ${MBMCParserTemplates.cef-malwarebytes-security-alert.Fields} [
      """msg=({additional_info}.+?)\s{0,100}\w+=""",
      """filePath=.*?(({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})(:({dest_port}\d{1,100}))?)"""
    ]
    DupFields = ["src_host->host"]
  }
cef-malwarebytes-security-alert = {
  Vendor = Malwarebytes
  Product = Malwarebytes Endpoint Protection
  Lms = ArcSight
  DataType = "alert"
  TimeFormat = "MMM dd yyyy HH:mm:ss"
  Fields = [
    """\Wrt=({time}\w+ \d{1,100} \d\d\d\d \d\d:\d\d:\d\d)""",
    """\Wdvchost=({host}[\w\-.]+)""",
    """({host}[\w\-.]+) CEF:""",
    """([^\|]*\|){6}({alert_severity}\d{1,100})""",
    """\Wdvchost=({src_host}[\w\-.]+)""",
    """\Wdvc=({src_ip}[A-Fa-f:\d.]+)""",
    """\WfilePath=({malware_url}[^=]+?)\s{0,100}(\w+=|$)""",
    """\WfileType=({additional_info}[^=]+?)\s{0,100}(\w+=|$)""",
    """Process name:\s{0,100}({process}({directory}[^=]*?)(\\+({process_name}[^\\]+?))?)\s{0,100}(\w+=|$)""",
    """\Wcs1=({alert_name}[^=]+?)\s{0,100}(\w+=|$)""",
    """\Wcat=({alert_type}[^=]+?)\s{0,100}(\w+=|$)""",
    """\Wsuser=({user}[^=]*?)\s{0,100}(\w+=|$)""",
    """\Wact=({action}[^=]+?)\s{0,100}(\w+=|$)"""
  ]

```