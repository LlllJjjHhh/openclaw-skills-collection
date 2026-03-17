# Daily Quote Skill for OpenClaw

OpenClaw 每日语录提醒技能。

## 功能

- 每日定时发送励志语录
- 随机获取一条语录
- 支持添加自定义语录

## 安装

```bash
cp -r openclaw-skills-collection/skills/quote-daily-skill ~/.openclaw/skills/
```

## 使用

- 获取随机语录：`给我来一句鸡汤` / `今日语录`
- 添加语录：`添加语录: 这句话很有用 -- 作者名`

## Configuration

在cron中配置每日提醒：
```
# 每天早上9点发送
schedule:
  kind: cron
  expr: 0 9 * * *
```

## License

MIT
