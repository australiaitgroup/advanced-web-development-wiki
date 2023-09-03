# Node.js学习
## HTTP methods CURD(Create, Update, Read, Delete)
Get：从Server获取资源
POST：在Server新建资源
DELETE：从服务器删去资源
## Status Code
### 2 - 成功 
200: OK 请求成功。一般用于 GET 与 POST请求。  
201:Created 已创建。成功请求并创建了新的资源。   
204 (无内容) 服务器成功处理了请求，但没有返回任何内容。 
### 3 - 重定向/没有修改/缓存 
304 (未修改) 自从上次请求后，请求的网页未修改过。服务器返回此响应时，不会返回网页内容。 
### 4 - 出错（client side） 
400 (错误请求) 服务器不理解请求的语法。  
401 (未授权)请求要求身份验证。对于需要登录的网页，服务器可能返回此响应。  
403 (禁止)服务器拒绝请求。  
404 (未找到) 服务器找不到请求的网页。 
### 5 - 出错 （server side） 
500 内部服务器错误。
## Query String 🆚 Params
### Query string
查询字符串位于‘？’之后，由键值对组成，键值对由‘&’间隔开。  
e.g. http://example/search?A=node&B=react
### Params
路由参数是路径的一部分，表示某个资源或者资源集合。  
e.g. http://example/students/123456

