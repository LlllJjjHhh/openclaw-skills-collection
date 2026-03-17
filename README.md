# OpenClaw Skills Collection

🤖 A collection of custom OpenClaw agent skills.

OpenClaw 是一个开源个人AI助手框架，支持自定义技能扩展。这里收集了我自己开发的实用技能。

## 📚 技能列表

| 技能 | 描述 | 分类 |
|------|------|------|
| [excel-utils-skill](./skills/excel-utils-skill) | Excel批量处理技能，支持合并、转换、清洗、统计 | 工具 |
| [quote-daily-skill](./skills/quote-daily-skill) | 每日语录打卡技能，发送今日格言 | 工具 |
| [bilibili-downloader-skill](./skills/bilibili-downloader-skill) | B站视频下载器，支持批量下载和音频提取 | 工具 |
| [ai-chat-skill](./skills/ai-chat-skill) | 本地大模型聊天技能，集成chat-llm-webui | AI/大模型 |
| [image-generate-skill](./skills/image-generate-skill) | AI图像生成技能，调用本地Stable Diffusion | AI/画图 |

## 🚀 安装技能

1. 克隆仓库：
```bash
cd ~/.openclaw/skills
git clone https://github.com/LlllJjjHhh/openclaw-skills-collection.git
```

2. 复制你想要的技能到skills目录：
```bash
cp -r openclaw-skills-collection/skills/your-skill ~/.openclaw/skills/
```

3. 重启OpenClaw生效

## 📝 开发自己的技能

按照OpenClaw Skill规范开发：
- 每个技能一个文件夹
- SKILL.md 描述技能功能和用法
- 必要的脚本和配置文件

详细开发文档参考：[OpenClaw Docs](https://docs.openclaw.ai)

## 🎯 特性

- ✅ 完全兼容OpenClaw技能规范
- ✅ 每个技能独立可拆分
- ✅ 文档完整，易于使用
- ✅ 持续更新

## 🤝 贡献

欢迎提交Issue和Pull Request添加更多技能！

## 📄 License

MIT

---

If this collection helped you, buy me a coffee ☕

<img src="Qrcode.jpg" alt="Buy Me A Coffee" width="300">
