## webhost自动化批量保号，每月1号自动登录一次面板，并且发送消息到Telegram

### 将代码fork到你的仓库并运行的操作步骤

#### 1. Fork 仓库

#### 2. 设置 GitHub Secrets

1. **创建 Telegram Bot**
    - 在 Telegram 中找到 `@BotFather`，创建一个新 Bot，并获取 API Token和 Chat ID
 
2. **配置 GitHub Secrets**
    - 转到你 fork 的仓库页面。
    - 点击 `Settings`，然后在左侧菜单中选择 `Secrets`
    - 添加以下 Secrets：
        - `WEBHOST`: 账号:密码 账号:密码 账号:密码
        - `TELEGRAM_BOT_TOKEN`: 你的 Telegram Bot 的 API Token
        - `TELEGRAM_CHAT_ID`: 你的 Telegram Chat ID
        
#### 3. 启动 GitHub Actions
