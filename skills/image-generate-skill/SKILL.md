# Image Generation Skill for OpenClaw

OpenClaw AI图像生成技能，集成Stable Diffusion。

## 功能

- 文生图，直接在OpenClaw中生成AI图像
- 支持参数调节（尺寸、步数、CFG）
- 支持多种Stable Diffusion模型

## 安装

```bash
cp -r openclaw-skills-collection/skills/image-generate-skill ~/.openclaw/skills/
```

## Requirements

- PyTorch
- diffusers
- 本地Stable Diffusion模型

## 使用

```
帮我生成一张图片: a beautiful sunset over the ocean
生成一张赛博朋克风格的城市夜景
```

## License

MIT
