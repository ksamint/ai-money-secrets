# AI Money Secrets 🤖💰

> 收集 AI 变现、副业、赚钱的优质情报

## 数据概览

- **总条目数**: 42 条
- **最后更新**: 2026-10-11
- **最后新增**: 2026-10-10
- **数据来源**: 知乎、CSDN、少数派、36氪、腾讯新闻、小报童 等

## 来源分布

| 来源 | 条目数 |
|------|--------|
| 知乎 | 8 |
| CSDN博客 | 6 |
| 少数派 | 5 |
| YouTube | 2 |
| u-chuhai.com | 2 |
| DeepSeek技术社区 | 2 |
| 其他 | 17 |

## 搜索关键词覆盖

- site:sspai.com AI变现 副业 赚钱
- AI副业 变现 方法 真实案例 2025
- ChatGPT Midjourney 副业 变现 教程
- AI独立开发者 赚钱 经验 2025
- AI工具 副业赚钱 实战

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
cat secrets.json | jq '.[] | select(.source=="知乎")'

# 查看最近数据
cat secrets.json | jq '.[] | select(.collected_at>"2026-10-01")'
```

## 贡献

通过 GitHub Issues 提交新的情报链接，或提交 PR。

## License

MIT
