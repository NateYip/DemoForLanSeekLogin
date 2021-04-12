# README

## 如何启动项目

> step1：启动web服务器，加载前端

运行 ./nginx/nginx.exe 

> step2：启动后端服务

运行./backendForWindows.exe

> step3：查看效果

点击浏览器输入http://localhost:80

效果如下:

> ![image-20210411163724643](C:\Users\nateyip\AppData\Roaming\Typora\typora-user-images\image-20210411163724643.png)



## Demo逻辑介绍

#### step1：点击Register注册一个新账号，点击注册

![image-20210411164311426](C:\Users\nateyip\AppData\Roaming\Typora\typora-user-images\image-20210411164311426.png)



#### step2：进入内容界面

> 在这里，你可以点击左边导航栏，切换 info 和 todoList 的界面

![image-20210411164544725](C:\Users\nateyip\AppData\Roaming\Typora\typora-user-images\image-20210411164544725.png)

#### step3：在Info界面

----

##### 点击Info的Fix按钮，你可以修改具体Info，点击完成可以看到Info被修改

![image-20210411164835982](C:\Users\nateyip\AppData\Roaming\Typora\typora-user-images\image-20210411164835982.png)

----



##### 点击Add to my TodoList，你会发现在todoList界面下有新的任务

![image-20210411165336285](C:\Users\nateyip\AppData\Roaming\Typora\typora-user-images\image-20210411165336285.png)

---



##### 上传新的Info

> 在上面的模块中可以添加新的Info，点击添加后，可以看见Info新添加了一条

##### ![image-20210411165606733](C:\Users\nateyip\AppData\Roaming\Typora\typora-user-images\image-20210411165606733.png)

---

##### 删除Info

> 直接点击Remove，可以直接删除Info



#### step4：在TodoList界面

同样的，具有和Info界面一样的功能（除了Fix）



## 前端目标

#### 初期阶段：

1. 完成上面的页面设计，尝试使用 Element UI 搭建页面。
2. 构建良好的路由文件，知道如何懒加载组件，知道路由跳转的具体逻辑。
3. 将用户的登录信息做保存，考虑如何做前端登陆检查。理解导航守卫是什么，该怎么去使用导航守卫。

#### 后期阶段：

1. 了解浏览器缓存机制，减少不必要的请求（强缓存、弱缓存是什么）。
2. 理解什么是预处理机制，尝试使用 defer 和 async。
3. 了解什么是展示组件和容器组件，尝试修改你的之前的项目，使得有更好的文件结构。
4. 什么是响应式流？增加一个搜索组件，尝试使用节流和防抖。
5. 理解什么是BFF，尝试搭建一个node服务器作为中间件（或许你需要解决跨域问题）。
6. 尝试使用Webpack打包你的项目。