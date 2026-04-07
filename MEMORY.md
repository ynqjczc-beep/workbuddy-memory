# 长期记忆 - 用户信息

## 用户基本信息
- **GitHub**: ynqjczc-beep
- **记忆仓库**: https://github.com/ynqjczc-beep/workbuddy-memory
- **本地记忆路径**: C:\Users\miaoh\WorkBuddy\Claw\.workbuddy\memory\

## 记忆机制（双重保险）

### 用户确认的备份方案
- 用户发消息 → 我自动写日记到本地
- 用户说"备份" → 立刻推送到 GitHub
- **用户忘了说备份** → 我自动每小时备份一次

### 存档流程
1. 对话中 → 随时把要点写入本地 YYYY-MM-DD.md
2. 用户说"备份" → 立刻推送到 GitHub
3. 每小时自动检查 → 如果有未备份的内容，自动推送

### 找回流程（自动）
1. 用户发现我忘了什么 → 说"我们聊过..."
2. 我主动从 GitHub 搜索所有备份记录
3. 找到相关内容后继续对话

### SSH配置
- SSH Key: C:/Users/miaoh/.ssh/workbuddy_memory
- GitHub仓库: git@github.com:ynqjczc-beep/workbuddy-memory.git
- **无需Token，通过SSH自动推送**

## 待补充
- 用户称呼/名字
- 所在城市
- 具体项目背景
