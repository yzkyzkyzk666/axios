# axios
axios learning
https://github.com/axios/axios

1.在浏览器中可以借助axios向服务端获取ajax请求来获取数据
2.axios在node.js中运行，向远端服务发送http请求

axios的请求响应结果的结构
config 配置对象，包括请求类型，请求url，请求体等数据
data 是响应体的结果（服务器返回结果（是一个对象）->因为axios自动讲服务器返回结果进行了json解析转成对象 方便我们处理）
headers 响应头信息
request 原生的ajax请求对象（XMLHttpRequest实例对象）， 保存的是当前axios在发送请求时所创建的ajax请求对象
        里面有 响应状态码status 和响应状态字符串statusText
