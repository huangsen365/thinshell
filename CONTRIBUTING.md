# 贡献指南 / Contributing Guide

不需要是学者，不需要懂区块链，不需要会写代码。  
只需要对"组织如何在 AI 时代运转"有真实的想法。

---

## 五条贡献路径

### 1. 提交 TSC 案例（最稀缺的贡献）

```bash
cp -r cases/_template cases/你的TSC名称
# 填写文件后提交 PR
```

**数据不完整没关系。真实 > 完整。**

### 2. 提 RFC（修改框架理论）

```bash
cp rfcs/_template.md rfcs/under-review/XXXX-你的标题.md
# 提交 PR，标题：[rfc] RFC-XXXX: 标题
```

### 3. 贡献工具实现

```
tools/contribution-token/implementations/  ← CT 系统实现
tools/agent-configs/                        ← Agent 配置模板
tools/contracts/                            ← 智能合约
```

一个 Notion 模板、一段 Prompt、一个脚本都算。但**必须真实用过**。

### 4. 完善法典模板

```
code/genesis/examples/          ← 行业特化创世层示例
code/operational/rule-library/  ← 操作层常用规则集
```

### 5. 翻译

目前有中文（主语言）和英文版本，其他语言欢迎社区贡献。  
先开 Issue 认领语言，再提交 PR。

---

## PR 标题格式

```
[whitepaper]  修正章节逻辑矛盾
[case]        添加 my-tsc 案例
[rfc]         RFC-XXXX: 描述
[tool]        描述
[code]        补充行业法典示例
[translation] [语言代码] 同步翻译
[fix]         修正错误
```

## 核心原则

- 大改动先开 Issue 讨论方向，再提 PR
- 案例和工具必须来自真实使用
- 失败案例与成功案例同样有价值

---

## Contributing (English)

No need to be an academic, blockchain expert, or coder.  
Just bring real thoughts about how organizations work in the AI age.

See the Chinese guide above — same rules apply.

First time? Open a [Discussion](https://github.com/cat9999aaa/thinshell/discussions) to introduce yourself.
