# SKYLENAGE-ReasoningMath
SKYLENAGE-ReasoningMath（推理数学评测集）覆盖从基础算术到高等数学的多层次推理任务，涵盖逻辑推导、代数变换、几何分析、概率统计等多个维度，旨在评估模型在结构化数学问题中的理解、推理与解答能力。数据集设计注重问题难度分级与认知层次划分，支持细粒度的能力评估。

本评测集的核心目标是突破当前主流评测中“重计算、轻逻辑”“重结果、轻过程”的局限，聚焦于三类在通用训练语料中覆盖不足、难以通过记忆或模式匹配完成的高阶推理任务：直觉逻辑、数论组合与空间推理。这三类能力不仅对模型的抽象思维水平构成挑战，也能够有效规避现有评测中的典型问题。

1.针对数据污染与记忆化作答问题，我们刻意避开高频题型，选择在互联网文本中低频甚至缺失的任务类型。直觉逻辑类任务涉及非标准化的多角色、多约束推理，其表述形式多样、解法路径不固定，难以被完整收录于训练数据中的；

2.数论组合问题强调构造性思维与数学直觉，而非公式套用，显著降低模型通过“见过类似题”而直接作答的可能性；

3.空间推理任务依赖对二维/三维结构的内在建模，以文本片段呈现空间推理任务让大模型进行复杂求解。

SKYLENAGE-ReasoningMath (Reasoning Math) covers multi-level reasoning tasks from basic arithmetic to advanced mathematics, encompassing logical deduction, algebraic transformations, geometric analysis, probability and statistics, and other dimensions. It aims to assess a model's ability to understand, reason, and solve structured mathematical problems. The dataset design emphasizes problem difficulty grading and cognitive level division, supporting fine-grained ability assessment.

The core goal of this dataset is to overcome the limitations of current mainstream assessments, which emphasize computation over logic and results over process. It focuses on three high-level reasoning tasks that are underrepresented in common training corpora and difficult to solve through memorization or pattern matching: intuitive logic, number theory combinatorics, and spatial reasoning. These three skills not only challenge the model's level of abstract thinking but also effectively avoid typical issues in existing assessments.

1. To address data contamination and memorization-based answering, we deliberately avoided high-frequency question types, selecting task types that are infrequent or even absent in online text. Intuitive logic tasks involve non-standardized multi-role, multi-constraint reasoning, with diverse expression forms and unfixed solution paths, making them difficult to fully capture in training data.

2. Number theory combinatorial problems emphasize constructive thinking and mathematical intuition rather than formulaic application, significantly reducing the likelihood of models simply answering based on "experienced similar problems";

3. Spatial reasoning tasks rely on intrinsic modeling of two-dimensional/three-dimensional structures. Presenting spatial reasoning tasks in text snippets allows large models to perform complex solutions.
