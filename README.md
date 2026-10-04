# 帝御技能库（Diyu Skill Library）

> 版本 v1.05 · 2026-10-05 · 主同步源：本仓库（GitHub）
> 帝御是融合《孙子兵法》与十四部经典精华的「内修心、外御势、中立己、御万物」决策心法体系。

## 这是什么

帝御是一套可执行的心法+策略框架，用于：人生抉择、项目取舍、竞争博弈、游戏对局分析、资源规划、心态修炼。
核心：**先定位处境（内/外/中立/兼有）→ 选诀落点 → 按模板输出可落地策略**。

- **内修（心法层）**：温良恭俭让 · 识践知旋 · 凝格恒戮
- **立己（主见层）**：独见守己（独/见/守/己）——世间规则多成全他人，唯独你要成全自我
- **外御（策略层）**：孙子兵法六步（先评估再决策，优先降低损失，重视虚实）
- **御物（总纲法则）**：天下无不可用之物，只有可用不可用、如何用、如何高效用

## 目录结构

```
帝御技能库/
├── 00_使用说明.md              # 给 AI / 使用者的快速指南
├── 01_帝御主框架/帝御-SKILL-v1.05.md   # ★ 核心框架（必读，含全部体系+14典精华）
├── 02_调度器/帝御-调度器-router.md     # 路由规则：需求→层/诀/典→对应文件
├── 03_典籍子技能/               # 14部典籍独立子技能（七段结构）
│   ├── 道德经.md 大学.md 中庸.md 传习录.md 庄子.md
│   ├── 三十六计.md 六韬.md 三略.md 吴子.md 司马法.md
│   └── 韩非子.md 鬼谷子.md 管子.md 商君书.md
└── 04_历史版本/                 # 按版本归档（Git 式）
```

## 给 AI 的读取指引

**最少只需读一个文件**：`01_帝御主框架/帝御-SKILL-v1.05.md`——它包含完整体系（五诀、独见守己、御物总纲、万法归宗+14部典籍精华映射），足以用帝御体系分析问题。

**完整读取**（可选）：主框架 + 调度器 + 需要的典籍子技能。

### 直链（AI 可访问）

raw 链接（更新即时生效，中文路径 AI 需自行编码）：

```
https://raw.githubusercontent.com/xianlideyuan-web/skills/main/帝御技能库/01_帝御主框架/帝御-SKILL-v1.05.md
https://raw.githubusercontent.com/xianlideyuan-web/skills/main/帝御技能库/02_调度器/帝御-调度器-router.md
https://raw.githubusercontent.com/xianlideyuan-web/skills/main/帝御技能库/03_典籍子技能/道德经.md
```

jsDelivr CDN 链接（自动编码、全球加速，更新后最长 12h 缓存）：

```
https://cdn.jsdelivr.net/gh/xianlideyuan-web/skills@main/帝御技能库/01_帝御主框架/帝御-SKILL-v1.05.md
https://cdn.jsdelivr.net/gh/xianlideyuan-web/skills@main/帝御技能库/02_调度器/帝御-调度器-router.md
https://cdn.jsdelivr.net/gh/xianlideyuan-web/skills@main/帝御技能库/03_典籍子技能/道德经.md
```

（其他 13 本子技能：把链接末尾的 `道德经` 换成对应典名即可。）

## 版本与发布

- 每次迭代（升级或修缮）自动同步：本仓库（GitHub）→ 飞书云盘 → 打包 zip 交付
- 历史版本归档于 `04_历史版本/`
- Gitee 镜像 `gitee.com/li-wanghua/skills` 自 2026-10-05 起停更

## 许可

公开仓库，全网可见，供学习使用。
