#### 安装
> + npm i express-generator -g  
> + express express-test
> + cd express-test 
> + npm i  
> + npm run start 
> 为了方便改代码后不用重启，我们使用  
> npm i nodemon cross-env --save-dev

####  介绍app-js
> 各个插件的作用    
> + http-errors:错误页处理
> + express
> + cookie-parse：只要经过这个中间件处理，我们纠结可以非常轻松的使用req.cookie()去访问所有cookie
> + morgan:记录access log
> + app.use(express.json()):post请求传入的数据直接在route中使用req.body获取
> + app.use(express.urlencoded({ extended: false }));：请求参数为application/x-www-form-urlencoded

#### 处理get和post请求
> res.json()

> 使用中间件
> + app.use()
> + next参数作用。