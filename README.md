# SKYLENAGE-ReasoningMath
SKYLENAGE-ReasoningMath（推理数学评测集）覆盖从基础算术到高等数学的多层次推理任务，涵盖逻辑推导、代数变换、几何分析、概率统计等多个维度，旨在评估模型在结构化数学问题中的理解、推理与解答能力。数据集设计注重问题难度分级与认知层次划分，支持细粒度的能力评估。

本评测集的核心目标是突破当前主流评测中“重计算、轻逻辑”“重结果、轻过程”的局限，聚焦于三类在通用训练语料中覆盖不足、难以通过记忆或模式匹配完成的高阶推理任务：直觉逻辑、数论组合与空间推理。这三类能力不仅对模型的抽象思维水平构成挑战，也能够有效规避现有评测中的典型问题。

1.针对数据污染与记忆化作答问题，我们刻意避开高频题型，选择在互联网文本中低频甚至缺失的任务类型。直觉逻辑类任务涉及非标准化的多角色、多约束推理，其表述形式多样、解法路径不固定，难以被完整收录于训练数据中的；

2.数论组合问题强调构造性思维与数学直觉，而非公式套用，显著降低模型通过“见过类似题”而直接作答的可能性；

3.空间推理任务依赖对二维/三维结构的内在建模，以文本片段呈现空间推理任务让大模型进行复杂求解。

SKYLENAGE‑ReasoningMath is a reasoning‑focused mathematics benchmark covering tasks from basic arithmetic to advanced topics, including logical deduction, algebraic manipulation, geometric analysis, probability and statistics, and related areas. It is designed to evaluate a model’s ability to understand, reason about, and solve structured mathematical problems. The benchmark features calibrated difficulty tiers and cognitive‑level stratification to support fine‑grained capability assessment.

The core objective is to address limitations of mainstream benchmarks—overweighting computation over logic and final answers over the reasoning process—by concentrating on three categories of high‑level reasoning tasks that are underrepresented in common training corpora and difficult to solve via memorization or pattern matching: intuitive logic, number theory and combinatorics, and spatial reasoning. These categories both stress a model’s capacity for abstract thinking and help mitigate common pitfalls in existing evaluations.

1. Data contamination and memorization. We intentionally avoid high‑frequency question patterns, selecting task types that are rare—or absent—in web text. Intuitive‑logic tasks involve non‑standard, multi‑entity, multi‑constraint reasoning with diverse problem formulations and non‑unique solution paths, making them unlikely to be comprehensively captured in training data.

2. Number theory and combinatorics. These problems emphasize constructive reasoning and mathematical intuition rather than formula plugging, substantially reducing the chance that a model answers simply because it has “seen a similar problem.”

3. Spatial reasoning. These tasks rely on internal representations of two‑ and three‑dimensional (2D/3D) structures; presenting them in a text‑only format requires large models to carry out complex spatial reasoning and problem‑solving.
