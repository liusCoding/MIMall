# 一.前端跨域解决方案
 **1.什么是前端跨域**

    跨域是浏览器为了安全而做出的限制策略

    浏览器请求必须遵循同源策略：同域名、同端口、同协议

**2.怎么解决前端跨域**

    1.CORS跨域
        CORS跨域- 服务端设置，前端直接头调用
        说明：后台允许前端某个站点进行访问

        安装axios ：npm i axios --save-dev
    2.JSONP跨域
        JSONP跨域-前端适配，后台配合
        说明：前后台同时改造

        安装jsonp：npm i jsonp --save-dev
    3.代理跨域

    