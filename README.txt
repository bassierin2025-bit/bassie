LISTENING DIARY APP

电脑本地使用：
1. 右键 start-app.ps1，选择“使用 PowerShell 运行”。
2. 浏览器会打开 http://localhost:8765。
3. 在 Chrome / Edge 地址栏右侧选择“安装应用”。

手机安装：
需要先把整个文件夹部署到支持 HTTPS 的网站空间，然后用手机浏览器打开网址。
Android Chrome：菜单 > 添加到主屏幕 / 安装应用。
iPhone Safari：分享 > 添加到主屏幕。

云端账户配置：
1. 在 Supabase SQL Editor 中执行 supabase-schema.sql。
2. 在 Authentication > Providers > Email 中关闭 Confirm email。
3. 把 Project URL 和 Publishable key 填进 supabase-config.js。
4. 把整个文件夹发布到 HTTPS 网站。

完成后即可使用“用户名 + 密码”注册登录。同一账户在手机和电脑上会自动读取同一份数据。
