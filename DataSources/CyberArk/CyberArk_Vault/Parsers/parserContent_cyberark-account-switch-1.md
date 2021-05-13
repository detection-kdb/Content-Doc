#### Parser Content
```Java
{
Name = cyberark-account-switch-1
  Vendor = CyberArk
  Product = CyberArk Vault
  Lms = Direct
  DataType = "account-switch"
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [  """;UsuarioCyberArk="""", """;Accion="Retrieve password"""", """;Safe="""" ]
  Fields = [
    """exabeam_time=({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
    """\w+\s{1,100}\d{1,100}\s{1,100}\d\d:\d\d:\d\d ({host}[\w\-.]+)""",
    """;Evento="({event_code}\d{1,100})""",
    """;IP_Origen="({src_ip}[A-Fa-f:\d.]+)""",
    """;Usuario="({account}[^\s"]+)""",
    """;IP="({dest_ip}[A-Fa-f:\d.]+)""",
    """;Safe="({safe_value}[^"]+)""",
    """;GatewayStation="(|({gateway_station}[^"]+))""",
    """;UsuarioCyberArk="({user}[^\s"]+)""",
  ]
}
```