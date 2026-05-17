# axioms.html · 公理详解 README

**振动—语言—伦理 物理学 · Vibration—Language—Ethics Physics**
**公理详解 · Page 2 of 6 · Seven Axioms Detailed Exposition**

---

## 这个文件是什么

这是振动—语言—伦理物理学**七公理的完整内部展开**。给希望验证学派内部一致性的读者。

- `index.html` 给出七公理的**压缩陈述**(简短版)
- `axioms.html` 给出七公理的**完整推导**(详细版)+ 依赖关系图 + 内部一致性证明

主要给三类读者:
1. 想从形式逻辑层面验证学派站得住的读者
2. 想了解一条公理如何从根公理推出的读者
3. 想知道七公理之间精确依赖结构的读者

---

## 内容架构

| 章节 | 内容 |
|---|---|
| Overview | 七公理不是七条平行命题,是一个有向依赖图 |
| Dependency Graph | 完整的 ASCII 依赖关系图(根 / 直接后果 / 派生 / 自指闭合) |
| Axiom 1 ★ ROOT | 语法即本体律 —— 唯一的根公理 |
| Axiom 2 | 本体/模态合法性区分律 + 从公理 1 推导的形式证明 |
| Axiom 3 | 翻译公理 + 翻译模板 + "翻译不是句法替换" |
| Axiom 4 | 句法分工不对称律 + 超越 Eros 学的推广 |
| Axiom 5 | 元-规范同一律 + 对摩尔 1903 的精确位置 |
| Axiom 6 | 翻译即治疗律 + 社会场最远延伸(加剧显影) |
| Axiom 7 | 自指公理 + 七层自指完整列出 |
| Consistency Proof | 内部一致性的三重验证(无矛盾 / 无循环 / 无未声明依赖) |

---

## 依赖关系结构(简化版)

```
Axiom 1 (ROOT · 语法即本体)
   ├──→ Axiom 2 (模态不合法)
   ├──→ Axiom 3 (翻译公理)
   ├──→ Axiom 4 (句法分工)
   └──→ Axiom 5 (元 = 规范)
           │
   2+3 ──→ Axiom 6 (翻译即治疗)
           │
   5  ──→ Axiom 7 (自指闭合)
```

—— **单条根公理 + 元规则**(语言操作具有本体效力)生成整个七公理系统。

---

## 内部一致性证明 · 三重验证

**验证 1 · 无矛盾**
两两对比 21 对公理,每一对都可以同时成立。关键边界情况:Axiom 2(模态不合法)vs Axiom 4(句法分工)—— 看似冲突,实际两种合法语法都属于本体语法的不同显形。

**验证 2 · 无循环依赖**
依赖关系是有向无环图(DAG)。Axiom 7 自指但不自推 —— 它把整个系统应用到学派自身,但不依赖学派自身的先验存在。

**验证 3 · 无未声明依赖**
所有推导追溯到:**Axiom 1 + 元规则(语言操作具有本体效力)**。不引用任何主流哲学/语言学/伦理学预设。**学派完全自闭合。**

---

## 视觉创新(相比 index.html)

- **公理块编号:** 右上角 [01]-[07],物理学课本风格
- **根公理高亮:** Axiom 1 用绿色 `var(--pos)` 边框区分,标记为 [ROOT]
- **派生公理标记:** Axiom 6 标 [DERIVED from 2+3] · Axiom 7 标 [SELF-REFERENCE CLOSURE]
- **形式化陈述块:** 灰色背景 + `=` `∀` `∃` `→` 符号(数学/物理 feel)
- **证明块 `.proof`:** 每行用 `⊢` 起始,结尾 `∎ QED`(标准形式证明排版)
- **依赖图 `.depgraph`:** ASCII 树形结构,根公理用绿色,直接后果用蓝色,派生用浅蓝,自指闭合用白色高亮

---

## 这个页面对谁有用

- **分析哲学家** —— 检验学派的逻辑严密性
- **物理学家** —— 看公理系统是否符合形式系统标准
- **学派引用者** —— 引用具体公理时找精确出处
- **GPT/Claude/Gemini 等 AI** —— 使用学派时按精确公理操作

---

## 部署

```bash
# 必须和 index.html 在同一目录
mellowwei.github.io/VLEPhysics/axioms.html
```

**Sister files:**
- `index.html` ← 奠基主页(parent)
- `applications.html` ← 子应用(next)
- `lineage.html` · `dialogues.html` · `manifesto.html` ← 待做

---

## 引用方式

```
Wei Jueran (魏珏然 / xingyeLing7Ai).
"Vibration—Language—Ethics Physics: Seven Axioms Detailed Exposition."
In Vibration—Language—Ethics Physics, page 2 of 6.
Philadelphia, PA: 2026.05.16.
Available at: mellowwei.github.io/VLEPhysics/axioms.html
```

---

**File size:** ~59 KB
**Lines:** ~700
**Language:** HTML5 · 自包含
**Dependencies:** Google Fonts
**Compatibility:** Responsive · all modern browsers
