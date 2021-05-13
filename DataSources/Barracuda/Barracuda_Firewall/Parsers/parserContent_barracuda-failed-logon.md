#### Parser Content
```Java
{
Name = barracuda-failed-logon
  DataType = "failed-logon"
  Conditions = [ """ LOGIN ATTEMPT: """, """ Security """, """: Denied: """, """: Login """, """box_Auth_access:""" ]
  Fields = ${BarracudaParserTemplates1.barracuda-logon-activity.Fields}[
    """Denied:\s({failure_reason}[^$]+?)\s{0,100}$"""
  ]
}
```