# 12306
原本是私人项目，但作者时间有限无法继续更新，因此交给广大coding伙计们。16年该项目可以实现登录、查票、刷票、查询订单、退订等功能。其中部分控件被我重写或修改。有些地方试试双击，比如席别那里，选择后想删除只要双击该席别就行。17年发现查票和提交订单功能无法使用，修复了查票功能，目前提交订单功能需要重写。 如果有大牛，请重构下该代码，实现界面、事件、逻辑分离。可以看到目前打开界面速度比较慢，因为有很多是请求了再加载。分离了界面就会非常快的展示出来，体验也会更好。  另外配置文件内置了我的12306账号，如果需要测试，请成功登录一次你的账号并选择记住密码，再不清空编译后目录时，成功登录的账号将会在被记住。