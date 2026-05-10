# Cache Optimizer Skill

通用 Token 缓存优化 Skill，适用于所有对话场景。基于 2025-2026 年最新的 Context Engineering（上下文工程）方法论，通过精简 Prompt、利用缓存机制、压缩历史对话等方式，在不影响回答质量的前提下减少 Token 消耗。

## 功能

- Context Engineering 上下文窗口优化
- Prompt Caching 缓存利用策略
- 历史对话摘要压缩
- RAG 文档处理优化
- 输出 Token 精简控制
- 模型分级调度建议
- 语义缓存复用

## 安装

### 方式一：对话安装

```
安装这个 skill：https://github.com/Rosenbad/cache-optimizer-skill
```

### 方式二：手动安装

将 `cache-optimizer` 文件夹复制到你的 AI 工具的 skills 目录：

| 工具 | 路径 |
|------|------|
| TRAE SOLO CN | `~/.trae-cn/skills/` |
| Claude Code | `~/.claude/skills/` |
| Cursor | `~/.cursor/skills/` |

## 自动触发

每次对话自动加载，适用于所有场景：
- 日常问答
- 代码开发
- 文档分析
- 长对话管理

## 预估节省

| 场景 | 节省 |
|------|------|
| 日常问答 | ~40% |
| 代码审查 | ~50% |
| 文档分析 | ~70% |
| 长对话 | ~50% |
| **综合平均** | **~55%** |

## 参考来源

- Context Engineering 方法论（2025）
- OpenAI / Claude / 阿里云百炼 Prompt Caching 官方文档
- OpenClaw Token 优化社区实践
- 大模型 Token 优化行业最佳实践

## License

MIT
