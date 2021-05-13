#### Parser Content
```Java
{
Name = specops-account-password-reset
  Vendor = Specops
  Product = Specops Password Reset
  Lms = Splunk
  DataType = "account-password-reset"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSSSSSSSZ"
  Conditions = [ """Specops Password Reset""", """<Event xmlns=""", """Password Reset Succeeded""" ]
  Fields = [
    """SystemTime='({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d{9}Z)'""",
    """({event_name}Password Reset Succeeded)""",
    """<EventID Qualifiers='0'>({event_code}\d{1,100})</EventID>"""
    """User:\s{1,100}'(({target_domain}[^\\\/']+)[\\\/])?({target_user}[^']+)'""",
    """<Computer>({host}[^<]+)</Computer>""",
    """From client:\s{1,100}'({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})'""",
  ]
}
```