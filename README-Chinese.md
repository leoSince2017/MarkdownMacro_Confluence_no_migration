Confluence Markdown Macro - no dependence of migration
========================

这个库来自Atlas-Authority/MarkdownMacro的直接克隆和修改，因为依赖“com.atlassian.migration”会导致bug，所以我不得不手动消去这个依赖，重新打包，来消去这个bug。

如果你和我遇到了同样的问题，那你可以（1）下载这个库的源码自己编译，或者（2）下载jar文件之后安装

## 如何从源码构建

如何从源码构建

（1）按照 https://developer.atlassian.com/server/framework/atlassian-sdk/install-the-atlassian-sdk-on-a-linux-or-mac-system/ 安装java jdk和 atlassian sdk

（2）下载这个库

（3）打开终端（cmd或者powershell或者bash或者什么的），运行 'atlas-run' （首次运行会下载和安装一系列东西，很慢，不要担心）

（4）如果能打开  http://localhost:1990/confluence 你就成功了。用户名密码都是“admin”

（5）掏出 target/目录下生成的 .jar 文件

（6）把这个jar文件安装到你的Confluence

# 如何把 .jar 文件安装到confluence

（1）打开confluence

（2）管理员登录

（3）设置-管理应用-右边“上传应用”

（4）上传.jar文件，安装
