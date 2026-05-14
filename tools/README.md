# Tools（工具实现）

白皮书描述了很多工具和机制，这个目录存放具体实现。

**大多数工具目前还没有实现，等你来做。**

---

## 目录结构

```
tools/
├── contribution-token/       贡献代币（CT）系统
│   ├── spec.md               规格说明（必读）
│   └── implementations/
│       ├── notion-based/     基于 Notion（推荐起点，最简单）
│       ├── github-based/     基于 GitHub 贡献记录
│       └── onchain-solana/   基于 Solana 链上实现
├── agent-configs/            AI Agent 配置模板
│   ├── strategic-agent.md   战略型（任务分解+协调）
│   ├── research-agent.md    研究型
│   └── monitor-agent.md     监控型
└── contracts/
    └── README.md             智能合约规划说明
```

---

## 最急需的实现（优先级排序）

1. **CT 系统的 Notion 实现** — 不需要区块链，Notion 数据库即可
2. **战略型 Agent 的通用 Prompt** — 任务分解+协调的基础配置
3. **多方分账的 Solana 合约** — 链上自动分账的最小可用版本
4. **法典健康检查脚本** — 检测临近日落的规则和潜在矛盾

如果你在实现其中任何一个，先开 [工具 Issue](https://github.com/cat9999aaa/thinshell/issues/new?template=4-tool.yml) 宣告，避免重复劳动。

---

## 贡献工具的要求

在文件头部注明：

```markdown
**贡献者**：@用户名  
**实际使用场景**：[在哪个 TSC 里用过这个工具]  
**已知局限**：[诚实说明工具的缺陷]  
**最后更新**：YYYY-MM-DD
```
