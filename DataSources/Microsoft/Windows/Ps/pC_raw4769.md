#### Parser Content
```Java
{
Name = raw-4769
    Vendor = Microsoft
    Product = Windows
    Lms = Direct
    DataType = "windows-4769"
    TimeFormat = "yyyy-MM-dd HH:mm:ss"
    Conditions = ["A Kerberos service ticket was requested", "Account Name:"]
    Fields = [
      """({event_name}A Kerberos service ticket was requested)""",
      """({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
      """({event_code}4769)""",
      """Account Name:\s{0,100}({user}[^@:\s;]{1,2000})(@({domain}[\w._\-]{1,2000}))?[\s;]{0,2000}Account Domain""",
      """Service Name:\s{0,100}({dest_host}[^\s;]{1,2000}\$)[\s;]{0,2000}Service ID""",
      """Service Name:\s{0,100}({service_name}[^\s;]{1,2000})[\s;]{0,2000}Service ID""",
      """Client Address:\s{0,100}(::[\w]{1,2000}:)?({src_ip}[a-fA-F:\d.]{1,2000})""",
      """Failure Code:\s{0,100}({result_code}.+?)[\s;]{0,2000}Transited Services""",
      """Ticket Options:\s{0,100}({ticket_options}.+?)[\s;]{0,2000}Ticket Encryption Type"""
      """Ticket Encryption Type:\s{0,100}({ticket_encryption_type}.+?)[\s;]{0,2000}Failure Code"""
    ]
  }
```