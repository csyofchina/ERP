#golangERP
后台：框架采用国人谢大开发的beego
前台:webpack2+vue2+vuex+vue-router
简化数据库表设计，取消表的创建者、更新者和用户的直接关联关系，orm上为操作者的ID，而非对象

clone工程到go的src目录下，工程文件夹的名字必须为golangERP，若要修改名字需要将代码中所有golangERP修改为工程文件夹的名字
在golangERP\web 目录下执行:npm install & npm run build 
回到golangERP目录下执行：bee run 
默认端口为8888