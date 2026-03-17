# Bilibili Downloader Skill for OpenClaw

OpenClaw B站视频下载技能，方便快速下载B站视频。

## 功能

- 下载单个B站视频 by URL
- 批量下载多个视频
- 支持只下载音频（MP3）
- 支持选择画质
- 支持cookie登录下载高清视频

## 安装

```bash
cp -r openclaw-skills-collection/skills/bilibili-downloader-skill ~/.openclaw/skills/
```

## 使用

在OpenClaw聊天中直接使用：

```
下载这个B站视频: https://www.bilibili.com/video/BV1xx411c7mD
只下载音频给我: https://www.bilibili.com/video/BV1xx411c7mD
批量下载这些B站视频
```

## 配置

支持配置输出目录和默认画质：

```yaml
output_dir: ~/Downloads/bilibili
default_quality: 1080p
cookie_file: ~/.config/bilibili-cookies.txt
```

## 依赖

需要安装：
```
you-get
```

自动安装，无需手动操作。

## License

MIT
