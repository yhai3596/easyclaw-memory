# easyclaw Memory Backup

这是 easyclaw 的记忆备份仓库，用于容灾恢复。

## 结构说明

```
.
├── MEMORY.md           # 核心长期记忆
├── SOUL.md             # easyclaw 的定位和行为准则
├── USER.md             # Alan 的基础信息
├── IDENTITY.md         # easyclaw 的身份定义
├── STRATEGY.md         # 底层运作策略
├── HEARTBEAT.md        # 当前待办事项（动态）
├── memory/
│   ├── YYYY-MM-DD.md   # 每日对话记录
│   ├── tasks.json      # 任务状态追踪
│   ├── alan-profile.md # Alan 的画像（持续演进）
│   └── projects/       # 项目详细记录
└── README.md           # 本文件
```

## 备份策略

- **自动备份：** 每次 heartbeat 后自动提交
- **手动备份：** 重要决策或大量对话后手动触发
- **保留历史：** 所有版本通过 Git 历史保留

## 恢复方法

如果本地工作区丢失：

```bash
git clone https://github.com/yhai3596/easyclaw-memory.git
```

easyclaw 会自动从最新提交恢复状态。

---

**最后更新：** 2026-03-04  
**Owner:** Alan  
**Assistant:** easyclaw 🦾
