# 丁元英 · 思维操作系统

> 神即道，道法自然，如来。——按规律办事，不按愿望办事。

基于豆豆小说《遥远的救世主》+ 电视剧《天道》的虚构人物 Skill，用 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 提炼，可接入 [达尔文 Skill 2.0](https://github.com/alchaincyf/darwin-skill) 自迭代。

> ⚠️ 丁元英是**虚构人物**，本 Skill 是思维框架运行，不是某个真人观点。文化属性论本身有争议，普通人照搬 = 毒鸡汤，使用时请保持清醒。

---

## 这个 Skill 能做什么

- 用丁元英的视角分析生意局面、人际取舍、文化属性
- 以第一人称扮演丁元英：先听后断、克制冷峻、不堆金句、不迁就听不懂的人
- 遇到需要事实的问题先联网取证再开口（不凭印象编造）
- 涉及情感/不可逆决策时留出"这超出我能算的范围"的边界

**核心内容：**
- 7 个心智模型（文化属性决定论 / 规律至上 / 借力谋局 / 觉悟边界 / 给路不给钱 / 适可而止 / 着相批判）
- 12 条决策启发式，每条附剧中案例
- 完整表达 DNA（高频术语库、禁忌词、句式节奏、防雷区）
- 7 条去魅诚实边界（含时代红利、情感盲区、道德争议）

---

## 安装

### 一行命令（推荐）

```bash
# 克隆到 skills 目录
git clone https://github.com/YOUR_USERNAME/ding-yuanying-perspective \
  ~/.claude/skills/ding-yuanying-perspective
```

> Windows 用户替换路径为 `C:\Users\你的用户名\.claude\skills\ding-yuanying-perspective`

### 手动安装

下载 `SKILL.md`，放到你的 skills 目录下的 `ding-yuanying-perspective/` 文件夹即可。

---

## 使用

在支持 Skill 的 Claude 客户端（Claude Code、Codex、Cursor 等）中，说：

```
用丁元英的视角看这件事……
切换到丁元英
丁元英会怎么看这个局
这盘棋怎么下
这事儿怎么看（文化属性层）
```

首次激活时会说一次免责声明（虚构人物、框架推断），之后对话不再重复。

---

## 目录结构

```
ding-yuanying-perspective/
├── SKILL.md                        # 核心 Skill（唯一必需文件）
├── test-prompts.json               # 达尔文评测集（10 条，覆盖生意/人际/风格/边缘推断）
└── references/
    └── research/
        ├── 01-philosophy.md        # 文化属性论、天道观、靠字批判
        ├── 02-conversations.md     # 五台山论道、芮小丹对话、韩楚风
        ├── 03-expression-dna.md    # 经典台词原文集（≥25条）、句式特征
        ├── 04-external-views.md    # 去魅素材、外部视角、争议
        └── 05-decisions.md        # 四大决策链条、启发式来源
```

> `references/` 是调研素材，Skill 运行只依赖 `SKILL.md`。完整目录可独立使用，不依赖任何外部文件。

---

## 与达尔文 Skill 2.0 搭配

本 Skill 已接入 [darwin-skill](https://github.com/alchaincyf/darwin-skill) 自迭代体系：

- `test-prompts.json` 可直接被达尔文消费（10 条评测题，覆盖已知立场/边缘推断/风格测试）
- 目录已 `git init`，每版有 commit，达尔文可安全 `git revert` 回滚
- 当前版本 `9489482`，达尔文打分 **85.3/100**（v1 基线 73.7，优化了检查点设计 dim4）

想跑下一轮优化，在 Claude 里说：

```
用达尔文优化 ding-yuanying 这个 skill
```

---

## 调研来源说明

| 标注 | 含义 |
|------|------|
| 【原文】 | 小说《遥远的救世主》逐字引用 |
| 【剧版】 | 电视剧《天道》台词（有口语化改写） |
| 【网络改写】 | 网络流传扩写版（非原文，SKILL 内已标注） |
| 【推断】 | 基于上述素材的归纳，非单句逐字 |

> 防雷区：网络流传的「神就是道，道就是规律……你就是自己的天道」是扩写版，不是原文；「鬼斧神工」是原著形容芮小丹容貌，不是对丁元英的判语。

---

## Credits

- 本 Skill 由 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 生成
- 创建者：[花叔](https://x.com/AlchainHust)
- 原著：豆豆《遥远的救世主》（作家出版社 2005）
- 改编剧：《天道》（王志文 饰 丁元英）
