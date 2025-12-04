## 🌟 服务简介

QoderCLI 是一个开源的代码智能分析与生成工具，专为开发者打造。通过集成大语言模型（LLM），QoderCLI
能够理解项目上下文、自动补全代码、生成单元测试、解释复杂逻辑，并支持多语言智能问答，显著提升开发效率与代码质量。

## 🚀 部署流程

1. 访问计算巢 QoderCLI
   社区版 [部署链接](https://computenest.console.aliyun.com/service/instance/create/cn-hangzhou?type=user&ServiceId=service-f0c8a4c89bf0492a9144)
   ，按页面提示填写部署参数：  
   ![image.png](1.jpg)

2. 参数配置完成后，系统将自动生成**费用预估明细**。确认资源配置无误后，点击 **下一步：确认订单**。

3. 在订单确认页，确认后点击 **立即创建** 开始部署。

4. 部署完成后，通过控制台远程连接ECS。 

5. 通过 TUI 登录 Qoder，在终端中启动 Qoder CLI
   ```bash
   qodercli
   ```
   
6. 在交互式提示符中，输入 /login

   ```bash
   /login
   ```
   
7. 选择需要的登录方式：

   login with browser: 这会在你的默认浏览器中打开登录页面以完成身份验证。

   login with qoder personal access token: 系统会提示你将 Qoder Personal Access Token 直接粘贴到终端。

在你做出选择后，应用会引导你完成最后的步骤。
你可以在[此页面获取 Personal Access Token](https://qoder.com/account/integrations)

## 📚 使用指南

使用请参考 QoderCLI [官方文档](https://docs.qoder.com/zh/cli/using-cli) 了解完整命令列表。