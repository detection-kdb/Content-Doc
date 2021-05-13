#### Parser Content
```Java
{
Name = f5-asm-alert-1
  Vendor = F5
  Product = F5 BIG-IP Application Security Manager (ASM)
  Lms = Direct
  DataType = "alert"
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [ """ ASM:""", """,web_application_name="""", """,response_code="""" ]
  Fields = [
    """date_time="({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
    """\d\d:\d\d:\d\d ({dest_host}[^\s]+) ASM:""",
    """unit_hostname="({host}[^"]+)""",
    """ip_client="({src_ip}[A-Fa-f:\d.]+)""",
    """UserID=({user}[^\s,]+)""",
    """username="(N\/A|({user}[^"]+))"""",
    """src_port="({src_port}\d{1,100})""",
    """dest_port="({dest_port}\d{1,100})""",
    """dest_ip="({dest_ip}[A-Fa-f:\d.]+)""",
    """uri="(\/|({malware_url}[^"]+?))\s{0,100}"""",
    """policy_name="({policy_name}[^"]+)"""",
    """policy_name="({alert_name}[^"]+)"""",
    """,violations="({alert_name}[^"]+)"""",
    """violation_rating="({alert_severity}[^"]+)"""",
    """protocol="({protocol}[^"]+)""",
    """protocol="({alert_type}[^"]+)""",
    """,attack_type="({alert_type}[^"]+)"""",
    """virus_name="(N\/A|({malware_file_name}[^"]+))"""",
    """Host:\s{0,100}({domain}[^"]+?)((\\r\\n|\s{1,100})[\w\-]+:|")""",
    """User-Agent:\s{0,100}({user_agent}[^"]+?)\s{0,100}(\\r\\n[\w\-]+:|")""",
    """User-Agent:\s{0,100}Mozilla\/.+?({browser}Chrome|Safari|Opera|(?:F|f)irefox|MSIE|Trident)""",
    """geo_location="(N\/A|({country}[^"]+))"""",
    """ip_address_intelligence="(N\/A|({ip_reputation}[^"]+))""""
  ]
}
```