# laozi-dao

一个从《道德经》蒸馏而成的轻量 Agent Skill，用老子的思维框架分析现代决策、领导、冲突、欲望、边界与长期行动。

本 skill 由 [book-to-skill](https://github.com/virgiliojr94/book-to-skill) 从公版《道德经》通行本生成。仓库只包含综合提炼的框架、现代应用方法和章节索引，不包含电子书原文。

## 安装

```bash
npx skills add https://github.com/Recoverever/laozi-dao --skill laozi-dao
```

## 使用

安装后可以直接提问：

- 用《道德经》的方法分析：我该不该辞职？
- 用老子的视角处理这场团队冲突。
- `$laozi-dao` 我最近越努力越焦虑，怎么办？

skill 会先诊断情境，选择一至三个相关原则，检查常见误用，再给出现代可执行建议。

## 文件

- `SKILL.md`：核心框架、回答协议和情境路由
- `chapters/`：8 个按主题组织的知识模块
- `glossary.md`：关键概念与章号
- `patterns.md`：可复用决策模式
- `cheatsheet.md`：快速判断和行动表

## 来源与说明

- 原作：《道德经》，老子（传）
- 底本：Project Gutenberg eBook #7337
- 原作版权状态：Project Gutenberg 标示为美国公版
- 本仓库内容为综合提炼与实践性解释，不主张唯一的训诂或学术解释
