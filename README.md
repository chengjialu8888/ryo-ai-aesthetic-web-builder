# Ryo AI Aesthetic Web Builder

> **High Aesthetic × High Conversion** — We solve the "pretty but useless vs optimized but ugly" dilemma.

## 核心价值 | Core Value

**为什么用 Ryo AI Builder？**

| 问题 | 传统方案 | **Ryo AI Builder** |
|------|---------|-------------------|
| 审美 | 模板堆砌 | Primitives-first，14视觉趋势×5品牌原型 |
| 转化 | 经验主义 | Julian公式：Desire − (Labor + Confusion) |
| 增长 | 漏斗思维 | Brian Balfour循环：Loops > Funnels |
| SEO | 关键词堆砌 | 内容优先，语义化架构 |
| A/B测试 | 手动创建 | 内置3种Hero变体自动生成 |
| 灵感 | 无系统来源 | Variant→Mobbin→Craftwork→Impeccable |

---

## 跨平台配置 | Platform Setup

### Cursor / Claude Code
```bash
# 方法1：复制规则文件
mkdir -p .cursor/rules
cp ryo-ai-aesthetic-web-builder/.cursor/rules/ryo-ai-aesthetic-web-builder.md .cursor/rules/

# 方法2：作为 skill 导入
# 在 Cursor Settings > Skills 中添加此文件夹路径
```

### OpenClaw
```bash
mkdir -p ~/.openclaw/skills
cp ryo-ai-aesthetic-web-builder/.openclaw/skills/ryo-ai-aesthetic-web-builder.md ~/.openclaw/skills/
```

### Codex CLI (OpenAI)
```bash
mkdir -p ~/.codex/skills
cp ryo-ai-aesthetic-web-builder/.codex/skills/ryo-ai-aesthetic-web-builder.md ~/.codex/skills/
```

### Gemini CLI
```bash
mkdir -p ~/.gemini/skills
cp ryo-ai-aesthetic-web-builder/.gemini/skills/ryo-ai-aesthetic-web-builder.md ~/.gemini/skills/
```

### Windsurf
```bash
mkdir -p .windsurf/rules
cp ryo-ai-aesthetic-web-builder/.windsurf/rules/ryo-ai-aesthetic-web-builder.md .windsurf/rules/
```

### Trae
```bash
mkdir -p .trae/rules
cp ryo-ai-aesthetic-web-builder/.trae/rules/ryo-ai-aesthetic-web-builder.md .trae/rules/
```

### 通用 Agents
```bash
mkdir -p ~/.agents/skills
cp ryo-ai-aesthetic-web-builder/.agents/skills/ryo-ai-aesthetic-web-builder.md ~/.agents/skills/
```

### Mira
在 Mira 技能中心上传 `.skill` 或 `.zip` 文件即可自动识别安装。

---

## 快速开始 | Quick Start

### 触发指令示例

**中文：**
- "根据这份文档做一个高品位 AI 网站"
- "帮我优化落地页转化率"
- "生成多版 Hero 文案做 A/B test"
- "按 Aesthetics of AI 的范式设计网站"
- "从 Mobbin 找类似的 UI 参考"

**English:**
- "Build a high-aesthetic AI website from this document"
- "Optimize my landing page conversion"
- "Generate multiple Hero variants for A/B testing"
- "Design a website following Aesthetics of AI principles"
- "Find UI references from Mobbin"

---

## 文件结构 | File Structure

```
ryo-ai-aesthetic-web-builder/
├── README.md                          # 中英双语文档
├── SKILL.md                           # 核心技能指令
├── references/
│   ├── aesthetics_of_ai_primitives.md # 14视觉趋势×5品牌原型
│   ├── growth_primitives.md           # Julian + Brian 增长方法论
│   ├── cursor_growth_case.md          # $0→$2B 案例拆解
│   └── design_inspiration_library.md  # Variant/Mobbin/Craftwork/Impeccable
├── scripts/
│   └── extract_text.py                # 文档解析工具
├── .cursor/rules/                     # Cursor / Claude Code
├── .codex/skills/                     # OpenAI Codex CLI
├── .gemini/skills/                    # Gemini CLI
├── .agents/skills/                    # Generic agents
├── .openclaw/skills/                  # OpenClaw
├── .windsurf/rules/                   # Windsurf
└── .trae/rules/                       # Trae
```

---

## 核心方法论 | Core Methodology

### 1. Aesthetic Layer (Aesthetics of AI)
- **14 Visual Trends**: Canvas×Signal, Playful Precision, Generative Organic, etc.
- **5 Brand Archetypes**: Likeable Leaders, Gentle Humanists, Nerdy Idealists, Bold Builders, Utopian Dreamers
- **Primitives-first**: Color, Typography, Layout, Texture, Motion as tokens

### 2. Conversion Layer (Julian Shapiro)
```
Purchase Rate = Desire − (Labor + Confusion)
```

**3 Hero A/B Variants:**
1. **Bold Claim** — Contrarian positioning
2. **Objection Killer** — Address pain points
3. **Story** — Emotional connection

### 3. Growth Layer (Brian Balfour)
**Loops > Funnels**

- **Content Loop**: UGC → SEO → Users
- **Product Loop**: Usage → Value → Sharing
- **Community Loop**: Engagement → Network → Advocacy

### 4. SEO Layer
- Topic clusters over keyword stuffing
- Pain-point driven content
- Schema markup implementation
- Internal linking strategy

---

## 质量指标 | Quality Benchmarks

| 指标 | 目标值 |
|------|--------|
| Page Load | < 2s |
| Core Web Vitals | Pass |
| Accessibility | WCAG 2.1 AA |
| SEO Score | > 90 |
| Conversion Rate | +30% vs baseline |

---

## 许可 | License

MIT License — 自由使用，欢迎贡献。

---

> "Design isn't decoration. It's communication with intent. Every pixel should earn its place." — Ryo Lu

> "Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away." — Antoine de Saint-Exupéry
