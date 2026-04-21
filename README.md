# openclaw

1. 手动启动网关命令
在终端（Terminal）中输入以下命令来手动启动网关服务：

Bash
openclaw gateway --port 18789
注意： 启动后，Codespaces 通常会弹出一个提示框，点击 “在浏览器中打开” (Open in Browser) 即可进入管理面板 
04:39
在新窗口中打开。

2. 获取并配置 Gateway Token
进入面板后，需要绑定 Token。如果终端没有直接显示，可以新建一个窗口并输入以下命令获取：

查看 Token：

Bash
openclaw status
复制返回结果中的 token 字符串，并粘贴到网页面板的 Gateway Token 栏位中，点击连接 
05:29
在新窗口中打开。

3. 设备授权 (Device Authentication)
为了让网页端正常访问，还需要进行手动授权：

在终端输入：

Bash
openclaw devices list
获取显示的 request_id 
06:04
在新窗口中打开。

在网页面板的授权界面，输入该 ID 完成手动授权。授权成功后刷新网页，状态将显示为 OK 
06:25
在新窗口中打开。

相关资源
官方配置文档： AnyRouter OpenClaw 教程

GitHub 代码空间： GitHub Codespaces

配置完成后，你可以通过面板自动配置 Claude 4.5 等顶级模型。目前 AnyRouter 在活动期间提供免费额度供用户测试使用 
09:13
在新窗口中打开。

你需要了解如何进一步配置特定的 AI 模型（如视频中提到的 Claude 4.5）吗？
