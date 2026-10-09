# CUHK SZ 会计面试准备 Skill

一个 **Claude Code skill**，帮助候选人准备**香港中文大学（深圳）会计硕士项目（MSc in Accounting）**的面试。

它把一份第一手面经整理成了「速查手册 + 模拟面试教练」二合一的工具。

## 它能做什么

- **速查手册**：面试流程（多轮次 / Zoom 双机位 / 15 分钟 / 全程英文）、三大核心问题、简历准备、当天注意事项、专业面权重。
- **模拟面试教练**：按真实流程用英文 mock —— 自我介绍 → 动机 / 简历 / 专业提问 → 反问，结束后用中文打分（聚焦面试官真正看重的「适配度 + 意愿度」）并给出可直接改口说的示范答案。

## 安装

1. 复制到个人 skills 目录：

   ```bash
   mkdir -p ~/.claude/skills
   cp -r SKILL.md references ~/.claude/skills/cuhksz-acct-interview/
   ```

   实际只需两个文件：

   - `SKILL.md` —— skill 主指令（教练逻辑 + 判分依据）
   - `references/playbook.md` —— 速查手册（全部要点）

2. 重启 Claude Code（或新开一个会话），skill 即生效。

## 使用

直接对话即可触发，例如：

- 「港中深会计面试流程是什么？」
- 「给我来一场 CUHK SZ 会计 mock interview」

## 目录结构

```
.
├── SKILL.md                          # skill 主指令
├── references/
│   └── playbook.md                   # 速查手册
├── CUHK SZ Acct 面试准备.pdf          # 原始面经出处
└── README.md
```

## 出处与免责声明

内容整理自一份候选人的个人面经（见同目录 PDF）。面试流程、重点与面试官偏好可能随年份、轮次变化，请以项目官网和最新面经为准。

## License

[MIT](LICENSE)
