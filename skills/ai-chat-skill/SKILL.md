# AI Chat Skill for OpenClaw

OpenClaw 本地大模型聊天技能。

## 功能

- 集成本地大模型（Qwen/ChatGLM/Llama）
- 流式对话体验
- 可调节生成参数
- 完全本地运行，隐私保护

## 安装

```bash
cp -r openclaw-skills-collection/skills/ai-chat-skill ~/.openclaw/skills/
```

## Requirements

- 本地部署大模型
- PyTorch, transformers
- chat-llm-webui 后端服务

## 使用

直接在OpenClaw中聊天，或者打开WebUI界面：

```
用本地大模型和我聊天：你好，请介绍一下自己
打开AI聊天界面
```

## Configuration

在skill config中设置：
```yaml
model_path: /path/to/your/model
api_url: http://localhost:5000
```

## License

MIT
