#### Parser Content
```Java
{
Name = okta-app-login-1
  Vendor = Okta
  Product = Okta Adaptive MFA
  Lms = Direct
  DataType = "app-login"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Conditions = [ """Start New Session""", """"tenantHost":""" ]
  Fields = [
    """exabeam_host=({host}[^\s]+)""",
    """"userAgent":\s{0,100}"({user_agent}[^"]+)""",
    """"userAgent":\s{0,100}"[^"]*({os}iOS|Android|BlackBerry|Windows Phone|BeOS|(?:X|x)11|(?:W|w)indows|(?:L|l)inux|(?:M|m)acintosh|(?:D|d)arwin)[^"]+?({browser}Chrome|Safari|Opera|(?:F|f)irefox|MSIE|Trident)""",
    """"requestTime":\s{0,100}"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d\d\dZ)""",
    """"deviceType":\s{0,100}"(login_type)""",
    """"systemAccount":\s{0,100}";*({user}[^;"]+)""",
    """"tenantHost":\s{0,100}"({app}[^"]+)""",
    """"activityAction":\s{0,100}"({activity}[^"]+)""",
    """"ipAddress":\s{0,100}"({src_ip}[^"]+)""",
    """"target":\s{0,100}\{[^\}]*"descriptor":\s{0,100}"({user}[^\/"]+?)\s{0,100}\/\s{0,100}({user_fullname}[^"]+)""",
  ]
}
```