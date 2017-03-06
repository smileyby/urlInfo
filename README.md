详解URL的组成
============

以下面的url为例，介绍下普通的URL的哥哥组成部分

http://www.aspxfans.com:8080/news/index.asp?boardID=5&ID=24618&page=1#name

> * 协议部分：该url的协议部分为 http: ,者代表网页使用的是http协议。在Internet中可以使用多种协议，如http，ftp等等本例中使用的是HTTP协议。在“http”后面的“//”为分隔符
> * 域名部分：该url的域名部分为“www.aspxfans.com”.一个url中，也可以使用ip地址作为域名使用
> * 端口部分：跟在域名后面的是端口，域名和端口之间使用“:”作为分隔符。端口不是一个url必须的部分，如果省略端口部分，将采用默认端口
> * 虚拟目录部分：从域名的第一个“/”开始到“?”为止，是虚拟目录部分。虚拟目录也不是url必须的部分。本例中的虚拟目录是“/news/”
> * 文件名部分：从域名后的最后一个“/”开始到“?”为止，如果没有“?”，则是从域名部分的最后一个“/”开始到“#”为止，是文件部分，如果没有“?”和“#”，那么从域名开始的最厚一个“/”开始到结束，都是文件名部分。本例中的文件名是“index.asp”。文件名部分也不是url必须的组成部分，如果省略该部分，则使用默认的文件名
> * 锚部分：从“#”开始到最厚，都是锚部分。本例中的锚部分是“name”。锚部分也不是一个url必须的部分
> * 参数部分：从“?”开始到“#”为止的部分为参数部分，又称搜索部分/查询部分。本例中参数部分为“boardID=5&ID=24618&page=1”。参数可以允许有多个参数，参数与参数之间哦那个“&”作为分隔符。

