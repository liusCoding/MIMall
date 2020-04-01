# 一.前端跨域解决方案
 **1.什么是前端跨域**

    跨域是浏览器为了安全而做出的限制策略

    浏览器请求必须遵循同源策略：同域名、同端口、同协议

**2.怎么解决前端跨域**

    1.CORS跨域
        CORS跨域- 服务端设置，前端直接头调用
        说明：后台允许前端某个站点进行访问
        Response Headers中：
        Access-Control-Allow-Credentials:true 如后端取不到你的cookie，前端发请求时一定要设置这个选项为true
        Access-Control-Allow-Origin: http://local:8080 此设置可允许前端跨域

        let url  = https://www.easy-mock.com/mock/5b012c1fe6e1035843cd3aff/mockapi/table/list

        安装axios ：npm i axios --save-dev
    2.JSONP跨域
        JSONP跨域-前端适配，后台配合
        说明：前后台同时改造

        安装jsonp：npm i jsonp --save-dev
    3.代理跨域

    