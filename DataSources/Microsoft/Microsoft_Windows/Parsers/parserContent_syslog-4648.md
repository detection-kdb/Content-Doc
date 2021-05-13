#### Parser Content
```Java
{
Name = syslog-4648
  Vendor = Microsoft
  Product = Microsoft Windows
  Lms = Direct
  DataType = "windows-account-switch"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss+SS:SS"
  Conditions = [ """EVENT_ID="4648"""", """EVENT_TASK="Logon"""", """A logon was attempted using explicit credentials""" ]
  Fields = [
    """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\+\d{1,100}:\d{1,100})\s({host}[^\s]+)""",
    """({event_name}A logon was attempted using explicit credentials)""",
    """sourceip="({src_ip}[A-Fa-f\d.:]+)"""",
    """EVENT_ID="{0,20}({event_code}\d{1,100})""",
    """EVENT_HOST="({host}[^"]+)""",
    """EVENT_USERNAME="(-|({domain}[^\\]+)\\+(-|({user}[^"]+)))""",
    """Logon ID:\s{1,100}({logon_id}[^\s]+)\s{1,100}Logon GUID"""
    """Subject(:|=)[\s;]*Security ID(:|=)\s{0,100}(\\NULL SID|({user_sid}[^=:]*?))[\s;]*Account Name(:|=)""",
    """Subject(:|=)[^"]+?Account Name(:|=)\s{0,100}(?:-|SYSTEM|({user}[^\s]*?))[\s;]*Account Domain(:|=)""",
    """Subject(:|=)[^"]+?Account Domain(:|=)\s{0,100}(?:-|NT Service|({domain}[^\s]*?))[\s;]*Logon ID(:|=)""",
    """Subject(:|=)[^"]+?Logon ID(:|=)\s{0,100}({logon_id}[^=:]*?)[\s;]*Logon GUID(:|=)""",
    """Subject(:|=)[^"]+?Logon GUID(:|=)\s{0,100}\{({user_logon_guid}[^}]+)\}[\s;]*Account Whose""",
    """Used(:|=);?\s{0,100}Account Name(:|=)\s{0,100}({account}[^\s;@]+?)(@({account_domain}[^\s;]+?))?[\s;]*Account Domain(:|=)"""
    """Used(:|=)[^"]+?Account Domain(:|=)\s{0,100}(|({account_domain}[^=:]*?))[\s;]*Logon GUID(:|=)""",
    """Used(:|=)[^"]+?Logon GUID(:|=)\s{0,100}\{({account_logon_guid}[^=:]*?)\}[\s;]*Target Server(:|=)""",
    """Target Server Name(:|=)\s{0,100}({dest_host}[^=:]*?)[\s;]*Additional Information(:|=)""",
    """Additional Information(:|=)\s{0,100}({dest_service}[^=:]*?)[\s;]*Process Information(:|=)""",
    """Process ID(:|=)\s{0,100}({process_id}[^=:]*?)[\s;]*Process Name(:|=)""",
    """Process Name(:|=)\s{0,100}(?:|({process}({directory}(?:[^"]+)?[\\\/])?\s{0,100}({process_name}[^\\\/]+?)))\s{1,100}Network""",
    """Network Address(:|=)\s{0,100}(?:-|({src_ip}[a-fA-F:\d.]+))"""
    ]
    DupFields = ["directory->process_directory"]
 
}  

  {   
    Name = raw-4648-1
    Vendor = Microsoft
    Product = Microsoft Windows
    Lms = Direct
    DataType = "windows-account-switch"
    TimeFormat = "yyyy-MM-dd HH:mm:ss"
    Conditions = ["A logon was attempted using explicit credentials", "Target Server Name", "dhn"]
    Fields = [
      """({event_name}A logon was attempted using explicit credentials)""",
      """({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
      """"dhn":"({host}[^-"]+)""",
      """({event_code}4648)""",
      """Subject(:|=)[\s;]*Security ID(:|=)\s{0,100}({user_sid}.*?)[\s;]*Account Name(:|=)""",
      """Subject(:|=).+?Account Name(:|=)\s{0,100}(?:-|SYSTEM|({user}[^\s]*?))[\s;]*Account Domain(:|=)""",
      """Subject(:|=).+?Account Domain(:|=)\s{0,100}(?:-|NT Service|({domain}[^\s]*?))[\s;]*Logon ID(:|=)""",
      """Subject(:|=).+?Logon ID(:|=)\s{0,100}({logon_id}.*?)[\s;]*Logon GUID(:|=)""",
      """Subject(:|=).+?Logon GUID(:|=)\s{0,100}\{({user_logon_guid}[^}]+)\}[\s;]*Account Whose""",
      """Used(:|=);?\s{0,100}Account Name(:|=)\s{0,100}({account}.*?)[\s;]*Account Domain(:|=)"""
      """Used(:|=).+?Account Domain(:|=)\s{0,100}(|({account_domain}.*?))[\s;]*Logon GUID(:|=)""",
      """Used(:|=).+?Logon GUID(:|=)\s{0,100}\{({account_logon_guid}.*?)\}[\s;]*Target Server(:|=)""",
      """Target Server Name(:|=)\s{0,100}({dest_host}.*?)[\s;]*Additional Information(:|=)""",
      """Additional Information(:|=)\s{0,100}({dest_service}.*?)[\s;]*Process Information(:|=)""",
      """Process ID(:|=)\s{0,100}({process_id}.*?)[\s;]*Process Name(:|=)""",
      """Process Name(:|=)\s{0,100}(?: |({process}({directory}(?:[^";]+)?[\\\/])?({process_name}[^\\\/";]+?)))[\s;]*Network Information(:|=)""",
      """Network Address(:|=)\s{0,100}(?:-|({src_ip}[a-fA-F:\d.]+))"""
    ]
    DupFields = ["directory->process_directory"]
  }
```