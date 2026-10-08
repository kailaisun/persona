# Wiki Persona · Values & Motivation 维度对照表

**Wiki Persona · Values & Motivation Dimensions — Bilingual Reference**

本文件列出 MatrAIx schema 中 `Values & Motivation` 类的全部 **46 个维度**，并给出 6 个 wiki 来源 persona 的真实取值，中英对照。

This document lists all **46 dimensions** of the `Values & Motivation` category in the MatrAIx schema, together with the actual values of 6 wiki-sourced personas.

| 项 | 说明 |
|---|---|
| 数据来源 / Source | MatrAIx Persona 1M 公共数据集 `MatrAIx2026/MatrAIx_Persona_1M_Public_Release` |
| 队列 / Cohort | `cohort-d14e9a8822bf`（与 10 人 Chat 测试同一 cohort） |
| Schema | `persona/schema/dimensions.json`（[MatrAIx-Persona-8B](https://github.com/MatrAIx-ai/MatrAIx-Persona-8B)） |
| 6 个 persona / personas | `Noah Patel`、`Jordan Patel`、`Priya Sharma`、`Noah Williams`、`Mateo Garcia`、`Omar Haddad` |

---

## 1. 维度定义 / Dimension definitions

`Values & Motivation` 是 schema 43 大类之一，共 46 个维度，分 5 个区块。

`Values & Motivation` is one of the 43 top-level categories, containing 46 dimensions in 5 blocks.

### 概览字段 / Overview fields

| # | Dimension ID | English label | 中文 | 取值 / Allowed values |
|---|---|---|---|---|
| 1 | `values_priority` | Core value | 首要价值取向 | Achievement（成就） / Security（安全） / Autonomy（自主） / Community（社群） / Novelty（新奇） / Tradition（传统） |
| 2 | `religiosity` | Religiosity | 宗教性 | Secular（世俗） / Spiritual（灵性） / Observant（虔敬） / Devout（虔诚） / Prefer not to say（不愿透露） |

### 价值观优先级 `val_*` / Value priorities

| # | Dimension ID | English label | 中文 | 取值 / Allowed values |
|---|---|---|---|---|
| 1 | `val_family` | Value: Family | 家庭 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 2 | `val_career_success` | Value: Career success | 事业成功 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 3 | `val_wealth` | Value: Wealth | 财富 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 4 | `val_health` | Value: Health | 健康 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 5 | `val_personal_freedom` | Value: Personal freedom | 个人自由 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 6 | `val_security_stability` | Value: Security & stability | 安全与稳定 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 7 | `val_adventure` | Value: Adventure | 冒险 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 8 | `val_tradition` | Value: Tradition | 传统 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 9 | `val_power_influence` | Value: Power & influence | 权力与影响 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 10 | `val_achievement` | Value: Achievement | 成就 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 11 | `val_creativity_self_expression` | Value: Creativity & self-expression | 创造力与自我表达 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 12 | `val_community` | Value: Community | 社群 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 13 | `val_spirituality_faith` | Value: Spirituality / faith | 灵性 / 信仰 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 14 | `val_knowledge_truth` | Value: Knowledge & truth | 知识与真理 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 15 | `val_social_status` | Value: Social status | 社会地位 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 16 | `val_independence` | Value: Independence | 独立 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 17 | `val_justice_fairness` | Value: Justice & fairness | 公正与公平 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 18 | `val_loyalty` | Value: Loyalty | 忠诚 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 19 | `val_sustainability` | Value: Sustainability | 可持续性 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 20 | `val_recognition` | Value: Recognition | 被认可 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 21 | `val_helping_others` | Value: Helping others | 帮助他人 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 22 | `val_personal_growth` | Value: Personal growth | 个人成长 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 23 | `val_fun_enjoyment` | Value: Fun & enjoyment | 乐趣与享受 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 24 | `val_integrity_honesty` | Value: Integrity & honesty | 正直与诚实 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 25 | `val_beauty_aesthetics` | Value: Beauty & aesthetics | 美与审美 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 26 | `val_order_structure` | Value: Order & structure | 秩序与结构 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 27 | `val_patriotism` | Value: Patriotism | 爱国 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 28 | `val_equality` | Value: Equality | 平等 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |
| 29 | `val_privacy` | Value: Privacy | 隐私 | Core value（核心价值） / Important（重要） / Moderate（中等） / Minor（次要） / Irrelevant（无关） |

### Schwartz 基本价值观 / Schwartz basic values

| # | Dimension ID | English label | 中文 | 取值 / Allowed values |
|---|---|---|---|---|
| 1 | `schwartz_value_self_direction` | Schwartz Self-Direction | 自我导向 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 2 | `schwartz_value_stimulation` | Schwartz Stimulation | 刺激 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 3 | `schwartz_value_hedonism` | Schwartz Hedonism | 享乐 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 4 | `schwartz_value_achievement` | Schwartz Achievement | 成就 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 5 | `schwartz_value_power` | Schwartz Power | 权力 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 6 | `schwartz_value_security` | Schwartz Security | 安全 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 7 | `schwartz_value_conformity` | Schwartz Conformity | 遵从 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 8 | `schwartz_value_tradition` | Schwartz Tradition | 传统 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 9 | `schwartz_value_benevolence` | Schwartz Benevolence | 仁善 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 10 | `schwartz_value_universalism` | Schwartz Universalism | 普世关怀 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |

### 自我决定论需求 / Self-determination needs

| # | Dimension ID | English label | 中文 | 取值 / Allowed values |
|---|---|---|---|---|
| 1 | `sdt_need_autonomy` | SDT Autonomy Need | 自主需求 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 2 | `sdt_need_competence` | SDT Competence Need | 胜任需求 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |
| 3 | `sdt_need_relatedness` | SDT Relatedness Need | 关联需求 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |

### 认知 / Cognition

| # | Dimension ID | English label | 中文 | 取值 / Allowed values |
|---|---|---|---|---|
| 1 | `need_for_cognition` | Need for Cognition | 认知需求 | Very high（极高） / High（高） / Average（中等） / Low（低） / Very low（极低） |

> 说明：`economic_motivation`（消费动机）在 schema 中不归入本类，但语义上属于价值取向，常用于定价类任务。
>
> Note: `economic_motivation` is not categorized under `Values & Motivation` in the schema, but is semantically a value orientation and is commonly used in pricing tasks.

---

## 2. 6 个 wiki persona 的实际取值 / Actual values (6 wiki personas)

下表按维度逐行给出 6 个 persona 的取值，`—` 表示该 persona 在此维度上没有值（源文本无依据，抽取时未赋值）。

The table below lists each dimension against the 6 personas. `—` means the persona has no value for that dimension (not grounded in the source text).

| Dimension ID | 中文 | Noah Patel | Jordan Patel | Priya Sharma | Noah Williams | Mateo Garcia | Omar Haddad | 6人中覆盖 |
|---|---|---|---|---|---|---|---|---|
| `values_priority` | 首要价值取向 | Achievement（成就） | Tradition（传统） | Achievement（成就） | — | Achievement（成就） | Achievement（成就） | 5/6 |
| `religiosity` | 宗教性 | Secular（世俗） | Secular（世俗） | — | — | — | — | 2/6 |
| `val_family` | 家庭 | Important（重要） | Important（重要） | — | Important（重要） | — | — | 3/6 |
| `val_career_success` | 事业成功 | Core value（核心价值） | Important（重要） | Core value（核心价值） | Minor（次要） | Core value（核心价值） | Important（重要） | 6/6 |
| `val_wealth` | 财富 | Core value（核心价值） | Irrelevant（无关） | — | Important（重要） | — | — | 3/6 |
| `val_health` | 健康 | Moderate（中等） | Irrelevant（无关） | — | — | — | — | 2/6 |
| `val_personal_freedom` | 个人自由 | Moderate（中等） | Moderate（中等） | — | Important（重要） | — | — | 3/6 |
| `val_security_stability` | 安全与稳定 | Important（重要） | Moderate（中等） | Important（重要） | Moderate（中等） | — | — | 4/6 |
| `val_adventure` | 冒险 | Minor（次要） | Moderate（中等） | — | Moderate（中等） | — | — | 3/6 |
| `val_tradition` | 传统 | Important（重要） | Core value（核心价值） | — | — | — | — | 2/6 |
| `val_power_influence` | 权力与影响 | Core value（核心价值） | Minor（次要） | Important（重要） | Minor（次要） | — | — | 4/6 |
| `val_achievement` | 成就 | Core value（核心价值） | Important（重要） | Core value（核心价值） | Minor（次要） | Core value（核心价值） | Important（重要） | 6/6 |
| `val_creativity_self_expression` | 创造力与自我表达 | Minor（次要） | Core value（核心价值） | — | — | Core value（核心价值） | — | 3/6 |
| `val_community` | 社群 | Important（重要） | Important（重要） | Important（重要） | — | — | — | 3/6 |
| `val_spirituality_faith` | 灵性 / 信仰 | Moderate（中等） | Moderate（中等） | — | — | — | — | 2/6 |
| `val_knowledge_truth` | 知识与真理 | Moderate（中等） | Important（重要） | Core value（核心价值） | Moderate（中等） | — | — | 4/6 |
| `val_social_status` | 社会地位 | Core value（核心价值） | Minor（次要） | Important（重要） | Important（重要） | — | — | 4/6 |
| `val_independence` | 独立 | Important（重要） | Important（重要） | — | Important（重要） | — | — | 3/6 |
| `val_justice_fairness` | 公正与公平 | Moderate（中等） | Irrelevant（无关） | — | — | — | — | 2/6 |
| `val_loyalty` | 忠诚 | Important（重要） | Important（重要） | — | Core value（核心价值） | — | — | 3/6 |
| `val_sustainability` | 可持续性 | Minor（次要） | Irrelevant（无关） | Core value（核心价值） | — | — | — | 3/6 |
| `val_recognition` | 被认可 | Core value（核心价值） | Important（重要） | Important（重要） | Minor（次要） | Important（重要） | — | 5/6 |
| `val_helping_others` | 帮助他人 | Moderate（中等） | Irrelevant（无关） | Important（重要） | — | — | — | 3/6 |
| `val_personal_growth` | 个人成长 | Important（重要） | Moderate（中等） | — | — | — | — | 2/6 |
| `val_fun_enjoyment` | 乐趣与享受 | Minor（次要） | Irrelevant（无关） | — | — | — | — | 2/6 |
| `val_integrity_honesty` | 正直与诚实 | Moderate（中等） | Important（重要） | — | Important（重要） | — | — | 3/6 |
| `val_beauty_aesthetics` | 美与审美 | Minor（次要） | Important（重要） | — | — | — | — | 2/6 |
| `val_order_structure` | 秩序与结构 | Important（重要） | Moderate（中等） | Important（重要） | — | — | — | 3/6 |
| `val_patriotism` | 爱国 | Important（重要） | Moderate（中等） | Core value（核心价值） | — | — | — | 3/6 |
| `val_equality` | 平等 | Moderate（中等） | Irrelevant（无关） | — | — | — | — | 2/6 |
| `val_privacy` | 隐私 | Minor（次要） | Irrelevant（无关） | — | — | — | — | 2/6 |
| `schwartz_value_self_direction` | 自我导向 | High（高） | High（高） | High（高） | High（高） | High（高） | — | 5/6 |
| `schwartz_value_stimulation` | 刺激 | Low（低） | Average（中等） | Average（中等） | Average（中等） | High（高） | — | 5/6 |
| `schwartz_value_hedonism` | 享乐 | Low（低） | Low（低） | Low（低） | Average（中等） | — | — | 4/6 |
| `schwartz_value_achievement` | 成就 | Very high（极高） | High（高） | Very high（极高） | Low（低） | High（高） | High（高） | 6/6 |
| `schwartz_value_power` | 权力 | Very high（极高） | Low（低） | High（高） | Low（低） | Low（低） | — | 5/6 |
| `schwartz_value_security` | 安全 | High（高） | Average（中等） | High（高） | High（高） | Average（中等） | — | 5/6 |
| `schwartz_value_conformity` | 遵从 | Average（中等） | Low（低） | Average（中等） | Average（中等） | Low（低） | — | 5/6 |
| `schwartz_value_tradition` | 传统 | High（高） | Very high（极高） | Low（低） | Average（中等） | Low（低） | — | 5/6 |
| `schwartz_value_benevolence` | 仁善 | Average（中等） | High（高） | High（高） | Very high（极高） | — | — | 4/6 |
| `schwartz_value_universalism` | 普世关怀 | Low（低） | Average（中等） | High（高） | — | — | — | 3/6 |
| `sdt_need_autonomy` | 自主需求 | High（高） | High（高） | High（高） | High（高） | High（高） | — | 5/6 |
| `sdt_need_competence` | 胜任需求 | Very high（极高） | High（高） | Very high（极高） | — | High（高） | High（高） | 5/6 |
| `sdt_need_relatedness` | 关联需求 | High（高） | High（高） | High（高） | Very high（极高） | — | — | 4/6 |
| `need_for_cognition` | 认知需求 | Average（中等） | High（高） | Very high（极高） | — | Average（中等） | — | 4/6 |

---

## 3. 覆盖率 / Coverage

- 6 个 wiki persona 都有的维度（3 个）/ Present in all 6: `val_career_success`, `val_achievement`, `schwartz_value_achievement`
- 每个 persona 在本类中实际有值的维度数 / Filled dimensions per persona：

| Persona | persona_id | 本类有值数 / filled |
|---|---|---|
| Noah Patel | `wiki-b44082b17a3c` | 46/46 |
| Jordan Patel | `wiki-b8c5cd8681b2` | 46/46 |
| Priya Sharma | `wiki-fc175eee7e27` | 27/46 |
| Noah Williams | `wiki-479d9840eba6` | 26/46 |
| Mateo Garcia | `wiki-968c45940489` | 15/46 |
| Omar Haddad | `wiki-c05382d41722` | 5/46 |

**结论 / Takeaway**：只有 `val_career_success`、`val_achievement`、`schwartz_value_achievement` 这 3 个维度在 6 个人里都稳定存在，是跨人格比较最安全的公共轴；其余 43 个维度覆盖率在 2/6–5/6 之间，`religiosity`、`val_family`、`val_wealth` 这类只有部分人有值。

**Takeaway**: Only 3 dimensions (`val_career_success`、`val_achievement`、`schwartz_value_achievement`) are present in all 6 profiles and are the safest common axes for cross-persona comparison. The other 43 dimensions are covered 2/6–5/6.

---

*生成自 MatrAIx Persona 1M（`cohort-d14e9a8822bf`），schema `v2`。 / Generated from MatrAIx Persona 1M (`cohort-d14e9a8822bf`), schema `v2`.*
