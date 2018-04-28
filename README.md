#blog
目录结构：
	db-          --数据库存储目录
	models       --数据库模型文件目录
	node_modules --node第三方模块目录
	public       --公共文件夹目录（css、js、img）
	routers      --路由文件目录
	schemas      --数据库结构文件目录
	views        --模板视图文件目录
	app.js       --应用启动入口文件
	package.json --第三方依赖
功能介绍：
	1.前台展示功能
		1》首页内容查看
		2》列表页-- 分类列表
		3》内容页-- 评论
		4》登陆、注册
	2、后台功能
		1》分类管理（对分类的增删改查）
		2》内容管理（对内容的的增删改查）
		3》查看用户
技术栈：
	1.nodejs
	2.express（简洁灵活的nodejs web应用框架，剔红了一系列强大的特性帮助我们创建各种web应用）
	3.mogodb（基于分布式文件存储的数据库，为web应用提供可扩展高性能的数据存储解决方案）
	4.第三方模块&中间件
		1》bodyParse：解析post请求数据
		2》cookie：读写cookie
		3》swig：js模板引擎解析
		4》mongoose：操作mongodb数据
使用:
	1.在node和mongodb官网安装这两个工具
	2.连接数据库，27017是默认的数据库端口号 通过管理员身份打开cmd.exe 进入到安装的mongodb的bin目录 输入 mongod --dbpath=博客的db文件夹目录 --port=27017 
	3.在博客当前目录中 node app.js