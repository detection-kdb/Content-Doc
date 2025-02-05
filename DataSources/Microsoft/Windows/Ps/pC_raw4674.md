#### Parser Content
```Java
{
Name = raw-4674
    Vendor = Microsoft
    Product = Windows
    Lms = Direct
    DataType = "windows-privileged-access"
    TimeFormat = "MMM dd HH:mm:ss yyyy"
    Conditions = ["An operation was attempted on a privileged object"]
    Fields = [
      """exabeam_host=([^=]{1,2000}?@\s{0,100})?({host}[\w.-]{1,2000})""",
      """({event_name}An operation was attempted on a privileged object)""",
      """({host}[\w\-.]{1,2000})\s{1,100}({time}\d{1,100}\/\d{1,100}\/\d{1,100}\s{1,100}\d{1,100}:\d{1,100}:\d{1,100}\s{1,100}(am|AM|pm|PM))""",
      """\scategoryOutcome=(|/({outcome}.+?))(\s{1,100}\w+=|\s{0,100}$)""",
      """({time}(?i)(Jan|Feb|Mar|Apr|May|Jun|Jul|Aug|Sep|Oct|Nov|Dec) \d{1,2} \d{1,2}:\d{1,2}:\d{1,2} 20\d{2})""",
      """({outcome}(?i)(((audit|success|failure)( |_)(success|audit|failure))|information))\s{0,100}(\s|\t|,|#\d{1,100}|<[^>]{1,2000}>)\s{0,100}({host}[^=]{1,2000}?)\s{0,100}(\s|\t|,|#\d{1,100}|<[^>]{1,2000}>)\s{0,100}""",
      """Event Type\s{0,100}:\s{0,100}({outcome}.+?)\.\s{1,100}Log Type""",
      """Type\s{0,100}=\s{0,100}"({outcome}[^";]{1,2000})"""",
      """Keywords=({outcome}.+?);?\s{0,100}Message=""",
      """\s{0,100}Source Address(:|=)\s{0,100}(?:-|({src_ip}[^\s]{1,2000}))\s{0,100}Source Port(:|=)""",
      """({event_code}4674)""",
      """Process Name(:|=)\s{0,100}(?: |({process}({directory}(?:[^";]{1,2000})?[\\\/])?({process_name}[^\\\/";]{1,2000}?)))[\s;]{0,2000}Requested""",
      """\s{0,100}Account Name(:|=)\s{0,100}(?:-|({user}.+?))[\s;]{0,2000}Account Domain(:|=)\s{0,100}({domain}.+?)[\s;]{0,2000}Logon ID(:|=)\s{0,100}({logon_id}.+?)[\s;]{0,2000}Object(:|=)""",
      """\s{0,100}Object Server(:|=)\s{0,100}({object_server}.+?)[\s;]{0,2000}Object Type(:|=)\s{0,100}(?:-|({object_type}.+?))[\s;]{0,2000}Object Name(:|=)\s{0,100}(?:|-|({object}.+?))[\s;]{0,2000}Object Handle""",
      """Desired Access(:|=)\s{0,100}({accesses}.+?)[\s;]{0,2000}Privileges(:|=)\s{0,100}({privileges}.+?)(\s{1,100}\d{1,100}|\"|,|;|\s{1,100}User:|\s$)""",
      """"Account":"((NT AUTHORITY|({domain}[^\\\s"]{1,2000}))\\+)?(LOCAL SERVICE|({user}[^\\\s"]{1,2000}))\s{0,100}"""",
      """"TargetAccount":"(({target_domain}[^\\\s"]{1,2000})\\+)?({target_user}[^\\\s"]{1,2000})""",
      """"SubjectUserSid":"({user_sid}[^\s"]{1,2000})""",
      """"SubjectLogonId":"({logon_id}[^\s"]{1,2000})""",
      """"ObjectServer":"(-|({object_server}[^\s"]{1,2000}))""",
      """"ObjectName":"(-|({object}[^\s"]{1,2000}))""",
      """"ObjectType":"(-|({object_type}[^\s"]{1,2000}))""",
      """"ProcessName":"(?: |({process}({directory}(?:[^";]{1,2000})?[\\\/])?({process_name}[^\\\/";]{1,2000}?)))\s{0,100}"""",
    ]
    DupFields = ["host->dest_host","directory->process_directory"]
  }
```