该仓库用于管理vscode mybatis 日志插件`mybatis-log-tygh`的`issues`。

This repository is used to manage issues for the VSCode MyBatis log plugin `mybatis-log-tygh`.

# 介绍/Introduction
为vscode进行springboot开发时，打印mybatis sql日志的插件  
A VSCode extension that prints MyBatis SQL logs during Spring Boot development.

# 注意事项/Notes
需要在launch.json中将需要启动的服务console设置为 "internalConsole"，列如  
You need to set the console of the service to be launched to "internalConsole" in launch.json, for example:
```json
    {
      "type": "java",
      "name": "DemoSingleApplication",
      "request": "launch",
      "mainClass": "com.tgh.DemoSingleApplication",
      "projectName": "demo-single",
      "console": "internalConsole"
    }
```
# 演示/Demo
![演示](../mybatis-log-tygh-issues/pic/vscode日志插件showcase.gif)
