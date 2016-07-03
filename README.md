# HTTPNetworking-

HTTP://在iOS9改为：HTTPS://
在Info.plist中添加NSAppTransportSecurity类型Dictionary。
在NSAppTransportSecurity下添加NSAllowsArbitraryLoads类型Boolean,值设为YES之后，把请求的URL都可以变成http而不是https了，如果还是https就报这个错。
