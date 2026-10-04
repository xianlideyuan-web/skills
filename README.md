# Skills 技能库集合（Skills Library）

> 本仓库是多个**平级技能库**的集合仓库（Git 式管理，公开可见）。
> 当前收录：**帝御技能库**。未来新增技能库将与帝御同层级，直接加在仓库根目录。

## 技能库清单

| 技能库 | 定位 | 版本 | 入口 |
| --- | --- | --- | --- |
| **帝御技能库** | 「内修心、外御势、中立己、御万物」决策心法体系（融合孙子兵法+十四部经典） | v1.05 | [进入 →](帝御技能库/00_使用说明.md) |

> 未来新增技能库：在根目录新建同名文件夹 + 在本表登记一行即可（结构见下）。

## 目录结构（多技能库平级）

```
skills/
├── README.md                    # 本门户页
├── 帝御技能库/                  # 技能库 #1（帝御）
│   ├── 00_使用说明.md
│   ├── 01_帝御主框架/帝御-SKILL-v1.05.md   # ★ 核心框架（必读）
│   ├── 02_调度器/帝御-调度器-router.md
│   ├── 03_典籍子技能/（14部典籍子技能）
│   └── 04_历史版本/
└── <未来技能库>/                # 技能库 #2、#3……（平级新增）
```

每个技能库统一结构：`00_使用说明.md` + `01_主框架/` + `02_调度器/` + `03_子技能/` + `04_历史版本/`。

---

## 帝御技能库 · 给 AI 的读取指引

**最少只需读一个文件**：`帝御技能库/01_帝御主框架/帝御-SKILL-v1.05.md`——包含完整体系（五诀、独见守己、御物总纲、万法归宗+14部典籍精华映射），足以用帝御体系分析问题。

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

### 版本与发布

- 每次迭代（升级或修缮）自动同步：本仓库（GitHub）→ 飞书云盘 → 打包 zip 交付
- 历史版本归档于各技能库 `04_历史版本/`
- Gitee 镜像 `gitee.com/li-wanghua/skills` 自 2026-10-05 起停更

## 许可

公开仓库，全网可见，供学习使用。
