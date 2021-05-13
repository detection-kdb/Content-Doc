#### Parser Content
```Java
{
Name = s-physical-badge-access-6
    Vendor = Badge
  Product = Badge
    Lms = Splunk
    DataType = "physical-access"
    TimeFormat = "MM/dd/yyyy HH:mm:ss"
    Conditions = ["AccessDescription","PersonnelID"]
    Fields = [
      """AccessFormatedTime"{1,20}:"{1,20}({time}\d\d/\d\d/\d\d\d\d \d\d:\d\d:\d\d)""",
      """AccesshostName":"({host}[^"]+)""",
      """PersonnelID":"({user}[^"]+)""",
      """PersonName":"({user_fullname}[^"]+)""",
      """PersonID":"({employee_id}[^"]+)""",
      """AccessDescription":"({outcome}[^"]+)""",
      """ReaderName":"({location_city}\w+)""",
      """ReaderName":"({location_door}[^"]+)"""
    ]
  }
```