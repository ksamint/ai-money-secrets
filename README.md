# AI Money Secrets 🤖💰

> 收集 AI 变现、副业、赚钱的优质情报

## 数据概览

- **总条目数**: 41 条
- **最后更新**: 2026-10-04
- **数据来源**: 知乎、CSDN、少数派、腾讯云、36氪 等

## 来源分布

| 来源 | 条目数 |
|------|--------|
| 知乎 | 8 |
| CSDN博客 | 5 |
| 少数派 | 5 |
| YouTube | 2 |
| u-chuhai.com | 2 |
| 其他 | 19 |

## 搜索关键词覆盖

- AI变现、副业、赚钱
- ChatGPT、Midjourney 副业教程
- AI独立开发者经验
- AI工具实战案例
- 独立开发者变现路径

## 数据格式

每条数据包含：
- `title`: 文章标题
- `url`: 原始链接
- `description`: 摘要描述
- `source`: 来源网站
- `query`: 搜索关键词
- `collected_at`: 采集日期

## 使用方式

```bash
# 查看所有数据
cat secrets.json | jq '.'

# 按来源筛选
cat secrets.json | jq '.[] | select(.source=="zhihu.com")'

# 查看最近数据
cat secrets.json | jq '.[] | select(.collected_at=="2026-10-04")'
```

## 贡献

通过 GitHub Issues 提交新的情报链接，或提交 PR。

## License

MIT
