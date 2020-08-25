# CppHttpDemo
light weight C++ httpserver and httpclient based on mongoose

client每次请求都是一个独立的请求
请求函数中加入回调用于处理网络返回
测试

可以用浏览器、或者其他工具提交url，查看网络请求返回

GET

请求 

http://localhost:7999/api/hello

结果

{ "result": welcome to httpserver }
POST

请求

http://localhost:7999/api/sum?n1=20&n2=18

结果

{ "result": 38 }
