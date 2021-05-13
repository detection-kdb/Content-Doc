#### Parser Content
```Java
{
Name = cef-zscaler-web-activity
  Vendor = Zscaler
  Product = Zscaler Internet Access
  Lms = ArcSight
  DataType = "web-activity"
  IsHVF = true
  TimeFormat = "epoch"
  Conditions = [ """|Zscaler|NSSWeblog|""", """requestClientApplication=""", """act=""" ]
  Fields = [
    """\srt=({time}\d{1,100})""",
    """\srt=({time}\w+ \d\d \d\d\d\d \d\d:\d\d:\d\d)""",
    """\d\d:\d\d:\d\d ({host}\S+) CEF:""",
    """\sdvchost=({host}[\w\-.]+)\s{0,100}(\w+=|$)""",
    """\ssrc=({src_ip}[a-fA-F:\d.]+)\s{0,100}(\w+=|$)""",
    """\sdst=({dest_ip}[a-fA-F:\d.]+)\s{0,100}(\w+=|$)""",
    """([^\|]*\|){5}({action}[^\|]+)""",
    """(\s|\|)act=({action}[^=]+?)\s{0,100}(\w+=|$)""",
    """\ssuser=(NA|None|\$NULL|(?![^\s]+@[^\s]+)({user}[^=]+?))\s{0,100}(\w+=|$)""",
    """\ssuser=({user_email}({user}[^\s@]+)@[^\s]+)\s{0,100}(\w+=|$)""",
    """\sapp=({protocol}[^=]+?)\s{0,100}(\w+=|$)""",
    """\srequestProtocol=({protocol}[^=]+?)\s{0,100}(\w+=|$)""",
    """\scs4=(None|({ransomware_name}[^=]+?))\s{0,100}(\w+=|$)""",
    """\srequest=({full_url}[^\s]+?)\s{1,100}(\w+=|$)""",
    """\srequest=(\w+:\/{2})?[^\/]+({uri_path}\/[^?\s]+)(\?\S+)?\s{1,100}(\w+=|$)""",
    """\srequest=(\w+:\/+)?[^|\/:]+(:\d{1,100})?[^|?]+({uri_query}\?[^\s]+)""",
    """\srequest=(?:[^:?]+:\/+)?({web_domain}[^\/:\s]+)""",
    """\srequest=[^\s?=]*?({top_domain}(?!(?:\d{1,100}\.){3}\d{1,100})[^\.\s]+(?=(?:\.(?:com|net|info|edu|org|gov|co|jp|ru|de|ir|it|in|fr|info|pl|nl|es|gr|cz|eu|tv|me|jp|ca|cn|uk|my|cc|id|us|nz|biz|club|io|gg|fi|au|st|tw|asia|sg|ie|li|za)(?::\d{1,100})?)+(?:\s\w+=|\/))[^\s:\/]+)""",
    """\srequestMethod=(NA|({method}[^=]+?))\s{0,100}(\w+=|$)""",
    """\srequestClientApplication=([uU]nknown|({user_agent}[^=]+?))\s{0,100}(\w+=|$)""",
    """\scn1=({risk_level}\d{1,100})""",
    """\sout=({bytes_in}\d{1,100})""",
    """\sin=({bytes_out}\d{1,100})""",
    """\scat=({category}[^=]+?)\s{0,20}\w+=""",
    """\sfileType=(None|({mime}[^=]+?))\s{0,100}(\w+=|$)""",
    """\soutcome=({result_code}\d{1,100})""",
    """\sreason=({proxy_action}[^=]+?)\s{0,100}(\w+=|$)""",
    """\srequestClientApplication=(?:-|Mozilla\/.+\(({os}iOS|Android|BlackBerry|Windows Phone|BeOS|(?:X|x)11|(?:W|w)indows|(?:L|l)inux|(?:M|m)acintosh|(?:D|d)arwin)[^=]+?([uU]nknown|({browser}Chrome|Safari|Opera|(?:F|f)irefox|MSIE|Trident)))""",
    """\scs1=({department}[^=]+?)\s{0,100}(\w+=|$)""",
    """\scs2=({categories}[^=]+?)\s{0,100}(\w+=|$)""",
    """\scs5=(None|({threat_name}[^=]+?))\s{0,100}(\w+=|$)""",
    """\scs6=(None|({dlp_engine}[^=]+?))\s{0,100}(\w+=|$)""",
    """sourcehost=(NA|None|\$NULL|({src_host}[^=]+?))\s{1,100}destinationhost=""",
    """destinationhost=(NA|None|\$NULL|({dest_host}[^=]+?))\s{1,100}\w+""",
    """devicehostname=({src_host}[^\s"]+?)\s{0,100}(\w+=|$)""",
    """ZscalerNSSWeblogDLPDictionaries=(None|({web_log_dict}[^=]+?))\s{0,100}([\w.]+=|$)"""
  ]
  DupFields = ["ransomware_name->threat_category", "risk_level->suspicious_content"]
}
```