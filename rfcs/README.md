# RFCs（框架进化提案）

RFC（Request for Comments）是 TSC 框架迭代自身的机制。

任何人都可以提 RFC。每个 RFC 都会认真讨论。无论接受还是拒绝，原因都公开记录。

---

## 目录

```
rfcs/
├── _template.md       从这里开始
├── accepted/          已接受并合并进框架
├── under-review/      正在讨论中
└── rejected/          已拒绝（永不删除）
```

---

## 提 RFC

```bash
cp rfcs/_template.md rfcs/under-review/XXXX-你的标题.md
# PR 标题：[rfc] RFC-XXXX: 标题
```

RFC 编号由维护者分配，提案时写 XXXX 即可。

---

## RFC 生命周期

```
草稿 → 讨论中（14天公示）→ 投票（3天）→ 接受 / 拒绝
```

被拒绝的 RFC 保留在 `rejected/`，附上原因，**永不删除**。

拒绝不是失败——"我们为什么不走这条路"本身就是有价值的记录。

---

## 已接受的 RFC

| 编号 | 标题 | 合并版本 |
|------|------|---------|
| [0001](./accepted/0001-initial-framework.md) | 初始框架建立 | v1.0.0 → v3.0.0 |

## 讨论中的 RFC

*（无，等待第一个社区 RFC）*
