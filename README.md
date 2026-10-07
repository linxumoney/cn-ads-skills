# 中文广告投放技能库 · CN Ads Skills

**专为中国市场设计的 AI Agent 广告投放与文案系统。**

---

## 之前 vs 之后

**之前：**
"精准触达目标用户，助力品牌增长"

**之后：**
"你不是不会投广告。

你只是从来没有人告诉你，
为什么你的广告会在前三秒被划走。"

同一个产品。
完全不同的结局。

---

大多数 AI 生成的广告文案长得一个样。

官方腔。
正确但无聊。
没人记住。

这个仓库解决这个问题。

它编码了以下内容的底层思维：

- 高转化的信息流广告
- 高成单的私域漏斗
- 精准的产品定位
- 让人看完就想下单的直效文案

不是提示词。

是**技能**。

---

## 这是什么

一套为 AI Agent 设计的广告投放技能库，专注于：

- 付费流量获取（巨量引擎 / 腾讯广告 / 朋友圈 / 小红书）
- 中式直效文案框架（痛点撬动 / 社会认同 / 对比机制）
- 产品卖点提炼与定位
- 私域漏斗设计（企微 / 社群 / 直播）
- 创意测试与数据诊断

每个技能：

- 聚焦一个问题
- 有明确观点
- 可单独使用，也可串联
- 针对中国用户的决策心理设计

---

## 为什么不一样

大多数 AI 营销工具优化的是**输出速度**。

这个库优化的是**思维质量**。

具体来说：

- 不猜受众是谁 — 精确定义她是谁
- 不先写文案 — 先搞清楚她在哪个认知阶段
- 不追求听起来厉害 — 追求让她想付钱
- 不只是创作 — 还要筛选、过滤、诊断

它融合了两种通常分开的能力：

### 文案脑

- 意识层级（改编自 Eugene Schwartz，本土化）
- 市场认知成熟度
- 独特机制与大创意
- 标题、开头、证据、异议处理、收尾

### 操盘脑

- 广告创意与角度
- 漏斗路径与转化逻辑
- 筛选与资格确认
- 测试与效果诊断

大多数系统只有一个。

这个两个都有。

---

## 运作方式

每个技能放在独立文件夹：

```
skills/<分类>/<技能名>/SKILL.md
```

每个技能定义：

- 何时使用
- 需要哪些输入
- 如何思考
- 输出什么
- 不该做什么

它们设计为可串联使用。

---

## 示例流程

构建一个私域获客活动：

```
avatar-extraction（用户画像提取）
→ offer-extraction（产品价值提炼）
→ awareness-mapper（意识阶段定位）
→ mechanism-builder（独特机制构建）
→ ad-angle-multiplier（广告角度扩展）
→ scroll-stopping-creative（停划创意）
→ conversion-path-builder（转化路径设计）
→ objection-crusher（异议处理）
→ generic-language-killer（官方腔清除）
```

最终产出：

- 清晰的产品定位
- 多个测试角度
- 高转化广告创意
- 完整的私域漏斗
- 有说服力的文案

---

## 示例输出

见：`/examples/private-domain-campaign.md`

---

## 核心技能分类

### 基础层（Foundations）

先搞清楚真相，再动笔。

- `avatar-extraction` — 用户画像提取
- `voice-of-customer` — 用户原话挖掘
- `offer-extraction` — 产品价值提炼

---

### 文案脑（Copy Chief）

中式直效文案框架。

- `awareness-mapper` — 意识阶段定位（本土化 Schwartz）
- `mechanism-builder` — 独特机制构建
- `headline-matrix` — 标题矩阵
- `objection-crusher` — 异议处理

---

### 操盘脑（Operator OS）

执行与规模化。

- `scroll-stopping-creative` — 停划创意
- `ad-angle-multiplier` — 广告角度扩展
- `conversion-path-builder` — 转化路径设计
- `performance-diagnosis` — 效果诊断

---

### 质检层（QA）

让输出真正有效。

- `generic-language-killer` — 官方腔清除
- `claim-checker` — 卖点可信度核查

---

### 编排器（Orchestrators）

预设的多技能组合流程。

- `full-funnel-orchestrator` — 完整漏斗活动编排

---

## 适合谁用

- 跑巨量/腾讯广告的投手，想要更好的创意和文案
- 自己投广告的创始人，不想靠直觉试错
- 想保持团队输出一致性的代理商
- 在构建 AI 驱动营销系统的操盘手

---

## 不是什么

- 不是通用内容营销模板
- 不是"帮我写10条小红书"的提示词
- 不是表面的营销框架

这是为以下场景设计的：

- 直接效果广告
- 付费流量
- 真实预算
- 真实后果

---

## 安装

兼容任何使用 Agent Skills 模式的 Agent。

安装到：

```
.agents/skills/
```

或 OpenClaw 工作区的：

```
skills/
```

兼容：

- OpenClaw
- Claude Code
- Cursor / Windsurf
- 自定义 Agent 框架

---

## 哲学

未来不是更好的提示词。

而是**更好的思维方式被编码进去**。

---

## 路线图

- 扩展文案库（直播话术 / 私信话术 / 朋友圈文案）
- 平台专属技能层（巨量 / 小红书 / 视频号）
- 高级漏斗编排
- 创意测试系统

---

## 许可证

MIT

---

## 作者

林序聊AI  
专注 AI 驱动的增长系统与中国市场广告运营  

- X：[@linxumoney](https://x.com/linxumoney)
- YouTube：[@LinXuMoney](https://www.youtube.com/@LinXuMoney)
- GitHub：[linxumoney](https://github.com/linxumoney)

---

如果你认真用这个库，它不只会改善你的广告。

它会改变你思考广告的方式。

---

## 关注我

如果这个仓库对你有用：

⭐ **Star 这个仓库** — 帮助更多人发现它

🐦 **关注 X** → [@linxumoney](https://x.com/linxumoney)  
每天分享 AI + 增长实战经验

📺 **订阅 YouTube** → [林序聊AI](https://www.youtube.com/@LinXuMoney)  
视频讲解 AI 工具如何用在真实业务中

## 商业授权

个人学习、研究、测试和非商业使用可以。商业使用请先联系 **linxu.money@gmail.com** 获得授权，详见 [COMMERCIAL-LICENSING.md](COMMERCIAL-LICENSING.md)。

