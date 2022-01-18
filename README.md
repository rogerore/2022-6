### 提示：UUID请使用UUID生成器，推荐[UUID Generator](https://www.uuidgenerator.net/)

### 提醒：滥用可能导致账户被删除！！！ 

## 服务端创建操作流程 
0）给本项目个stars

1）将本项目fork至自己仓库修改`Deploy to Heroku`按键指向地址为自己仓库地址

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/zoteqarer/duo-xay)  
2）点击上面紫色`Deploy to Heroku`，会跳转到heroku app创建页面，填上应用程序名、选择节点（美国或者欧洲）、自定义UUID码，其他建议保持默认，点击下面deploy，几秒后搞定！   

3）若出现`We couldn't deploy your app because the source code violates the Salesforce Acceptable Use and External-Facing Services Policy.`提示，则返回仓库，>`Setting`>`Repository name`修改仓库名。

4）然后修改app.json文件中的`name`、`description`值

5）再修改`Deploy to Heroku`按键指向地址为自己仓库地址，重复`2）`的操作

### 原作者项目地址：https://github.com/mixool/xrayku
