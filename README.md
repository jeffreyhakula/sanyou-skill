# 叁侑食堂 AI Skill

![Version](https://img.shields.io/badge/version-0.2.0-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Type](https://img.shields.io/badge/data-static-lightgrey)

这是一个 AI Skill——安装后，你的 AI 助手就能回答叁侑食堂的问题：在哪吃、几点开门、有什么招牌菜、能不能外卖、停车怎么停、Wi-Fi 密码是什么、店里电话多少。

合肥科学大道的家常食堂，现在有了自己的 AI 服务。

## 关于叁侑食堂

华地紫园小区里的小馆子，卤肉饭、牛肉饭、特色馄饨、中式糖水，家常做法，不整花里胡哨的。

| 项目 | 内容 |
|------|------|
| 餐厅名称 | 叁侑食堂 |
| 地址 | 合肥市科学大道华地紫园小区 |
| 营业时间 | 10:30 - 20:30（每日） |
| 电话 | 19956586923 |
| 堂食 | 6 张桌，无包厢，不需要排队 |

## 这个 Skill 能做什么

| 能力 | 你可以问 |
|------|----------|
| 餐厅信息 | "叁侑在哪？""几点开门？" |
| 菜品介绍 | "有什么好吃的？""招牌是什么？" |
| 外卖订餐 | "能送外卖吗？""怎么点外卖？" |
| 打包带走 | "能打包带走吗？" |
| 店内 Wi-Fi | "Wi-Fi 密码多少？" |
| 停车 | "停车方便吗？怎么停？" |
| 最新动态 | "有什么新品？最近有活动吗？" |
| 联系方式 | "店里电话是多少？" |

## 安装

### 最简单的方式：告诉你的 AI 助手

直接把下面这句话发给你的 AI 助手：

> 帮我安装叁侑食堂 Skill，仓库地址：https://github.com/jeffreyhakula/sanyou-skill

Agent 会自动克隆仓库并安装到对应的 Skill 目录。

### 手动安装

将本仓库克隆到你的 Skill 目录，不同 IDE 对应的路径：

| IDE | Skill 目录 |
|-----|------------|
| Claude Code | `~/.claude/skills/sanyou-skill/` |
| Cursor | `.cursor/skills/sanyou-skill/` |
| Windsurf | `.windsurf/skills/sanyou-skill/` |
| Trae | `.trae/skills/sanyou-skill/` |
| Qoder | `.qoder/skills/sanyou-skill/` |
| 通用 | `.agents/skills/sanyou-skill/` |

```bash
# 示例：安装到 Claude Code
git clone https://github.com/jeffreyhakula/sanyou-skill \
  ~/.claude/skills/sanyou-skill
```

只要目录下有 `SKILL.md`，AI 助手下次启动就会自动加载这个 Skill。

## 目录结构

```
sanyou-skill/
├── SKILL.md      # 核心文件：元数据 + Agent 指令
├── skill.json    # 机器可读配置（静态数据、品牌提示词）
├── README.md
└── LICENSE
```

## 版本

当前版本：0.2.0

## License

[MIT](LICENSE)
