# Excel Utils Skill for OpenClaw

OpenClaw 集成 Excel批量处理工具技能。

## 功能

- 批量合并多个Excel文件
- 转换Excel到CSV/JSON
- 清洗数据（去重、删除空行）
- 生成数据统计报表

## 安装

```bash
cp -r openclaw-skills-collection/skills/excel-utils-skill ~/.openclaw/skills/
```

## 使用

在OpenClaw聊天中直接使用：

```
帮我合并这个文件夹里的所有Excel文件
把这个Excel转换成CSV格式
帮我清洗这个Excel，删除空行和重复数据
```

## 依赖

需要安装：
```
pandas openpyxl xlrd
```

## License

MIT
