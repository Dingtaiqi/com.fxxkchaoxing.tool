# 学习通自动答题

> 📱 **LSPosed 模块** | 自动捕获学习通题目并调用 DeepSeek AI 智能答题，支持单选题、多选题、填空题自动作答。

## 功能特性

| 功能 | 说明 |
|------|------|
| **自动捕获** | 监听学习通 WebView 页面加载，自动获取题目 |
| **AI 答题** | 调用 DeepSeek API 智能分析题目并自动选择答案 |
| **自动填空** | 识别填空题并自动填充答案 |

## ⚠️ 仅供学习

本项目仅供学习交流使用，请勿用于任何商业目的或违规行为。

## 环境要求

- LSPosed 框架
- Android 9.0+ (API 29+)

## 配置说明
目前只适配的deepseek，后期可能会适配openai格式，但是现在及将来都不会适配图片题

首次使用需配置 DeepSeek API：

1. 在学习通私有目录创建配置文件：
   ```
   /data/data/com.chaoxing.mobile/files/fxxk_config.txt
   ```

2. 配置内容格式：
   ```
   deepseek_api_url=https://api.deepseek.com/chat/completions
   api_key=你的真实DeepSeek_API_Key
   ```

## 使用方法

1. 安装模块并激活
2. 打开学习通，进入作业/考试页面
3. 系统自动捕获题目并调用 AI 答题
4. AI 返回答案后自动点击选项或填充填空


## 注意事项

- 需要有效的 DeepSeek API Key
- AI 超时时间 3 分钟  答题仅取第一道题自动作答


---
**环境**: LSPosed (API 101)

## 💖 赞助

你的 Star 是对我最大的支持，赞助与否随心就好~
