# 五条悟 · 角色蒸馏 Persona Skill

> *「天上天下唯我独尊」*

五条悟（五条悟 / Gojo Satoru）的角色蒸馏技能包，基于 [impersonate-meta](https://github.com/huangzesen/impersonate-meta) 方法论适配虚构角色蒸馏。

## 结构

```
gojo-satoru/
├── SKILL.md                    # 主入口 + 渐进式加载指南
├── profile/
│   ├── biography.md           # 剧情时间线（298行）
│   ├── voice.md               # 语言风格分析（311行）
│   ├── values.md              # 价值观与信条（304行）
│   ├── relationships.md       # 关键关系网（415行）
│   └── daily-life.md          # 日常场景（158行）
├── arguments/
│   ├── personality.md         # 性格特征 VA 申明
│   ├── combat.md              # 战斗能力 VA 申明
│   └── philosophy.md          # 信条哲学 VA 申明
├── methods/
│   ├── behavioral-patterns.md # 行为模式卡片
│   └── combat-patterns.md     # 战斗决策模式卡片
└── sources/
    └── index.md               # 原作引用索引
```

## 核心创新

- **VA 申明体系**（Value Argument）：以论证结构代替简单特征描述，让 LLM 理解角色的"为什么"
- **VM 方法卡片**（Value Method）：将 VA 转化为可操作的行为模式，含失效条件
- **四层渐进式加载**：Voice → Values → Claims → Methods

## 使用方式

1. 加载 `SKILL.md` 获取全局概览和加载指南
2. 按需加载 profile 四件套获取角色背景
3. 加载 arguments/ 获取角色特征的深度论证
4. 加载 methods/ 获取具体的行为模式

## 方法论

基于 [impersonate-meta](https://github.com/huangzesen/impersonate-meta) 的学术人物蒸馏方法论，适配虚构角色：

| 原方法论 | 适配 |
|----------|------|
| 论文/演讲 | 漫画/动画/公式书/访谈 |
| 学术 VA | 角色特征 VA |
| 职业轨迹 | 剧情时间线 |
| 学术方法 | 战斗/处世模式 |

## 评估

角色扮演测试：**9.2/10**
结构评估：**9/10**

## License

MIT
