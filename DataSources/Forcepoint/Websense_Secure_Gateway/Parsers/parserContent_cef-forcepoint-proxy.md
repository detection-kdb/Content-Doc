#### Parser Content
```Java
{
Name = cef-forcepoint-proxy
    Vendor = Forcepoint
    Product = Websense Secure Gateway
    Lms = ArcSight
    DataType = "web-activity"
    IsHVF = true
    TimeFormat = "epoch_sec"
    Conditions = [ "CEF","""|Forcepoint|""",""" app=""", """ request="""]
    Fields = [
      """\srt=({time}\d{10})""",
      """exabeam_host=({host}[^\s]+)""",
      """\sdvc=(-|({host}[^\s]+))""",
      """\sdvchost=({host}[^\s]+)""",
      """\sshost=({src_host}[^\s]+)""",
      """\sdst=({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})""",
      """\ssrc=({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})""",
      """\sspt=({src_port}\d{1,100})""",
      """\sdpt=({dest_port}\d{1,100})""",
      """\ssuser=(-|(?:\w+:\/+[\w.\-]+)\s{1,100}({user_ou}[^\/]+)\/({user_fullname}[^=]+?))\s{1,100}\w+=""",
      """\sact=({action}[^=]+?)\s\w+=""",
      """\srequestMethod=(?:-|({method}[^=]+?))\s\w+=""",
      """\sin=({bytes_out}\d{1,100})""",
      """\sout=({bytes_in}\d{1,100})""",
      """\sapp=(?:-|({protocol}[^=]+?))\s\w+=""",
      """\srequestProtocol=(?:-|({protocol}[^=]+?))\s\w+=""",
      """\sdhost=(?:|({web_domain}[^=]+?))\s\w+=""",
      """\srequest=({full_url}\S+)""",
      """\srequest=(?:-|(\w+:\/+[^\/]+({uri_path}\/[^\s\?]+)({uri_query}\?[^\s]+)?))\s{1,100}\w+=""",
      """\srequestUrlFileName=(?:|({uri_path}[^=]+?))\s\w+=""",
      """\srequestUrlQuery=(?:|({uri_query}[^=]+?))\s\w+=""",
      """\srequestClientApplication=(?:-|({user_agent}[^=]+?))\s{1,100}(\w+=|$)""",
      """CEF:([^\|]+\|){4}({category}[^\|]+)\|""",
      """\scs4=({category}[^=]+?)(\s{1,100}\w+=|;)""",
      """\scs5=({sub_category}[^=]+?)(\s{1,100}\w+=|;)""",
      """\sflexString1=(?:User Defined[^=]+?|({category}[^=]+?))\s{1,100}\w+=""",
      """\sflexString2=(?:User Defined.+?|({sub_category}.+?))\s{1,100}\w+=""",
      """\scs3=(?:-|({mime}[^=]+?))(\s{1,100}\w+=|;)""",
      """\sdhost=([^=]*?)({top_domain}[^.\s\/:]+(?=(?:\.(?:com|net|info|edu|org|gov|co|jp|ru|de|ir|it|in|fr|info|pl|nl|es|gr|cz|eu|tv|me|jp|ca|cn|uk|my|cc|id|us|nz|biz|club|io|gg|fi|au|st|tw|asia|sg|ie|li|za))+\s\w+=)[^=]+?)\s\w+=""",
      """\srequestClientApplication=(?:-|({browser}[\w\-]+))""",
      """\srequestClientApplication=(?:-|({browser}[\w\-]+)\/[\d\._]+)""",
      """\srequestClientApplication=(?:-|({browser}[^\/]+)[^=]+({os}iOS|Android|BlackBerry|Windows Phone|BeOS|(?:W|w)indows|(?:L|l)inux|(?:M|m)acintosh|(?:D|d)arwin))""",
      """\srequestClientApplication=(?:-|Mozilla\/[^=]+\(({os}iOS|Android|BlackBerry|Windows Phone|BeOS|(?:X|x)11|(?:W|w)indows|(?:L|l)inux|(?:M|m)acintosh|(?:D|d)arwin)[^=]+?({browser}Chrome|Safari|Opera|(?:F|f)irefox|MSIE|Trident))""",
      """\srequestClientApplication=(?:-|Mozilla\/[^=]+\((?:BeOS|(?:X|x)11|(?:W|w)indows|(?:L|l)inux|(?:M|m)acintosh|(?:D|d)arwin)[^=]+Gecko\/\d{1,100}\s{1,100}({browser}\w+))""",
      """suser=(-|({user_lastname}[^,]+),\s({user_firstname}([A-Za-z]+){1}(\s\w){0,1}))\s""",
      """suser=\w+:\/+([^\s]+)?\s{0,100}((CN|OU)\\+=[^,]+,){1,2}DC\\=[^,]+,DC\\=[^\/]+\/({user_fullname}({user_lastname}[^\\]+)\\+,\s{0,100}({user_firstname}[^=]+?))\s\w+=""",
      """loginID=(-|({user}[^\s=]+?))\s\w+="""
    ]
  }
```