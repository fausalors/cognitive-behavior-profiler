# Cognitive Behavior Profiler

一个基于法庭语言学、博弈论和状态机理论的文本逆向分析 Skill，用于对角色对话日志进行认知侧写与行为预测。

适用于 [AstrBot](https://github.com/AstrBotDevs/AstrBot) Skill 系统。

## 它能做什么

给定一段角色的对话日志，该 Skill 会将文本视为物理证据，通过逆向工程推导出角色的：

- 底层认知算法与核心驱动力
- 信任分配策略与防御机制
- 压力场景下的行为预测

所有分析结论必须有文本证据支撑，拒绝模糊泛用的巴纳姆式描述。

## 分析流程

1. **法庭语言学提取** — 高频词汇、句法结构偏好、情绪锚点识别
2. **状态机逆向** — 从 Input/Output 推导隐藏状态与防御机制
3. **博弈资源分析** — 信任资产与情绪负债评估
4. **诊断报告输出** — 证据链、认知算法、压力测试预测、综合标签

## 使用方式

**本地导入方法**
  1. 将 `SKILL.md` 放入 AstrBot 的 `data/skills/cognitive-behavior-profiler/` 目录下(在 astrbot 的 ./data/skills/ 下执行```git clone https://github.com/fausalors/cognitive-behavior-profiler.git```)
  2. 检查在 AstrBot 中是否已启用该 Skill - 若无显示，则 restart astrbot
  3. 向 Bot 提供角色对话日志，并要求进行人格侧写 / 认知分析 / 行为预测

**WebUI方法**
  1. 在 [releases](https://github.com/fausalors/cognitive-behavior-profiler/releases) 中下载 .zip 文件
  2. 通过 Astrbot 的 WebUI 中的 上传 Skills 进行上传
  3. 向 Bot 提供角色对话日志，并要求进行人格侧写 / 认知分析 / 行为预测
### 示例 Prompt

```
请对以下对话日志中的角色A进行认知侧写：

[粘贴对话日志]
```

## 输出示例

分析报告包含四个部分：

- 🗂️ **证据链存档** — 文本片段与语言学映射
- ⚙️ **底层认知算法** — 核心驱动力、信任策略、防御触发条件
- 🔮 **压力测试与行为预测** — 极端场景下的高概率反应
- 🏷️ **角色综合标签** — 3-5 个精准性格描述词（禁止巴纳姆标签）

## 安装

```bash
cd your-astrbot/data/skills/
git clone https://github.com/fausalors/cognitive-behavior-profiler.git
```

## License

MIT License
