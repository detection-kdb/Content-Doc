#### Parser Content
```Java
{
Name = q-okta-failed-app-login-2
  DataType = "failed-app-login"
  Conditions = [ """message""", """Active Directory authentication failed""", """published""" ]
  Fields = ${OktaParserTemplates.q-okta-app-login.Fields}[
    """"Active Directory authentication failed:\s{0,100}({failure_reason}[^"]+?)""""
  ]
}
q-okta-app-login = {
  Vendor = Okta
  Product = Okta Adaptive MFA
  Lms = QRadar
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Fields = [
    """exabeam_host=({host}[\w.\-]+)""",
    """"published"{1,20}:"{1,20}({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d{1,100}Z)""",
    """"message"{1,20}:"{1,20}({event_name}.+?)\s{0,100}(\.|\[|")""",
    """"ipAddress"{1,20}:"{1,20}({src_ip}[a-fA-F\d.:]+)""",
    """"displayName"{1,20}:"{1,20}((?i)Unknown|RSA-OKTA Admin|AD-OKTA Admin|({user_fullname}[^"]+))",[^\{\}]*?"objectType"{1,20}:"{1,20}User"""",
    """"login"{1,20}:"{1,20}({user_email}[^"@]+@({email_domain}[^"@]+))[^\{\}]*?"objectType"{1,20}:"{1,20}User"""",
    """"id"{1,20}:"{1,20}({user_agent}[^"]+)",[^\{\}]*?"objectType"{1,20}:"{1,20}Client"""",
    """"displayName"{1,20}:"{1,20}(UNKNOWN|({browser}[^"]+))",[^\{\}]*?"objectType"{1,20}:"{1,20}Client"""",
    """({app}Okta)""",
    """"displayName"{1,20}:"{1,20}({app}[^"]+)",[^\{\}]*?"objectType"{1,20}:"{1,20}AppInstance"""",
    """"categories.*?objectType"{1,20}:"{1,20}({activity}[^"]+)"""",
  ]

```