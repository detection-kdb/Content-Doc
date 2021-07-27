#### Parser Content
```Java
{
Name = sentinelone-web-activity
  DataType = "web-activity"
  Conditions = [ """CEF:""", """dproc=Deep Visibility Endpoint""", """destinationServiceName=SentinelOne""", """method:""", """http {""" ]
  Fields = ${SentinelOneParserTemplates.sentinelone-activity.Fields} [
    """method:\s{0,100}"{1,20}({method}[^"]{1,2000})"""
    """url:\s{0,100}"{1,20}({full_url}({protocol}[^:\\\/\s,"]{1,2000}):\/*({web_domain}[^\\\/\s:,"]{1,2000})(:({dest_port}\d{1,100}))?({uri_path}\/[^\s\?"]{0,2000})?({uri_query}\?[^"\s]{0,2000})?)"""    
  ]
}
```