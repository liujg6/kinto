* Kintohub已经封了这个项目，所以只能部署到Heroku了，下面是部署到Heroku的方法。
* Heroku也封了这个项目，可以fork本项目，修改项目名和部署链接，即可正常部署。

部署链接格式如下，等号后面改成你fork过去的项目链接：
`https://dashboard.heroku.com/new?template=https://github.com/liujg6/kinto`

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/liujg6/kinto)

#### 部署服务端

点击上面紫色`Deploy to Heroku`，会跳转到heroku app创建页面，填上app的名字，最后换上从 https://111111.online/getuuid.html 拷贝过来的UUID，点击下面deploy创建APP，完成后会生成一个链接，点击链接显示“Bad Request”就说明部署成功了！
