# Vue-order

基于vue.js+node.js+mongodb开发的订餐系统，代码注释详细，适合初学者.


PS：并不是所有页面都是用Vue.js做前台数据绑定，只是**订餐页**使用了Vue.js做数据的展示；
其他页面因Node.js方便而用了ejs渲染，样式使用Boostrap3。

**本版本还在继续开发中……在线演示版本为**[bae分支](https://github.com/giscafer/Vue-order/tree/bae)

<a href="http://vueorder.duapp.com/" target="_blank">http://vueorder.duapp.com/</a>



# 功能

 - 注册+登录（注册含有效验证，激活，密码找回等整套流程）

 - 订餐功能
 
 - 评论回复
 
 - 后台用户管理和餐馆信息维护功能

 - 统计功能（计划……）

 - 在线实时对话功能（计划……）

 - Vue.js + Webpack 开发App端（计划……）
 

# 使用
**1、安装**

本地安装`MongoDB`数据库和`Node`环境后，进入项目根目录下使用`npm install`下载依赖包。

**2、配置文件**

将`src/server/config.default.js`重命名为`config.js`，然后根据注释说明修改即可。
管理员权限需要在`config.js`里边配置
```
     //超级管理员账户（user_login_name: true ）
    admins: {
        giscafer:true
    }

```
只有配置了超级管理员权限的用户登录才能看到管理员权限的相关功能模块

**3、运行**

    node app.js

# SCREENSHOT

![overview][1]
![manger][2]
![userlist][3]
![setting][4]

[1]: https://github.com/giscafer/Vue-order/blob/master/src/assets/overview1.0.png
[2]: https://github.com/giscafer/Vue-order/blob/master/src/assets/manager.png
[3]: https://github.com/giscafer/Vue-order/blob/master/src/assets/userlist.png
[4]: https://github.com/giscafer/Vue-order/blob/master/src/assets/setting.png
