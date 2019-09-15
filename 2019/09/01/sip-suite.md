## 组件选型
### SIP Server
Opensips据说电信行业内部使用的就是该组件，https://www.oschina.net/question/5189_8848。如果说该组件不提供媒体功能，那么非常棒，只需要在完成信令的陆游，应答和传输后，由后续的媒体服务器完成即可。

### JS客户端
jssip
虽然作者并没有说明支持opensips，但是基于对老外的契约精神的理解，我认为是支持的。中文示例代码：https://www.cnblogs.com/benmumu/p/8316670.html

### Android客户端
Android SIP API: 据说有阉割，但可以确认下是否满足要求；
JAIN-SIP: Oracle官方标准，如果Android端不支持则使用该组件；
