blog：[这里阅读] (http://haoyaxin.github.io)

## hexo基本操作
### 安装
`sudo npm install -g hexo`
### 生成静态文件
`hexo generate` 或 `hexo g`
### 配置github
修改【_config.yml】
```
deploy:

     type: git

     repo: https://github.com/leopardpan/haoyaxin.github.io.git

     branch: master
 ```
     
执行
`npm install hexo-deployer-git --save`
     
### 部署
`hexo deploy` 或 `hexo d`
###常用命令

`hexo new"postName"` #新建文章

`hexo new page"pageName"` #新建页面

`hexo generate` #生成静态页面至public目录

`hexo server` #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）

`hexo deploy` #将.deploy目录部署到GitHub

`hexo help` # 查看帮助

`hexo version` #查看Hexo的版本
