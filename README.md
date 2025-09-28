# SKYLENAGE-ReasoningMath

[![魔搭社区](https://img.shields.io/badge/ModeScope-🏠-blue.svg)](https://modelscope.cn/datasets/Alibaba-DT/SKYLENAGE-ReasoningMATH)
[![Dataset-HF](https://img.shields.io/badge/Data-Huggingface-orange.svg)](https://huggingface.co/datasets/alibabagroup/SKYLENAGE-ReasoningMath) 

# I. 基准介绍
SKYLENAGE-ReasoningMath（推理数学评测集）覆盖从基础算术到高等数学的多层次推理任务，涵盖逻辑推导、代数变换、几何分析、概率统计等多个维度，旨在评估模型在结构化数学问题中的理解、推理与解答能力。数据集设计注重问题难度分级与认知层次划分，支持细粒度的能力评估。

数据集介绍：

ReasoningMath.json为数据文件，总计开源100道题，包括了序号，难度，学科分类，题目，最终解答。

部分题目附录.xlsx为部分题目解答附录，总计开源30道题，包括了序号，思维链分析标准，解题分析标准。

SKYLENAGE Technical Report.pdf为技术报告。



# II. 基准特性
本评测集的核心目标是突破当前主流评测中“重计算、轻逻辑”“重结果、轻过程”的局限，聚焦于三类在通用训练语料中覆盖不足、难以通过记忆或模式匹配完成的高阶推理任务：直觉逻辑、数论组合与空间推理。这三类能力不仅对模型的抽象思维水平构成挑战，也能够有效规避现有评测中的典型问题。

1.针对数据污染与记忆化作答问题，我们刻意避开高频题型，选择在互联网文本中低频甚至缺失的任务类型。直觉逻辑类任务涉及非标准化的多角色、多约束推理，其表述形式多样、解法路径不固定，难以被完整收录于训练数据中的；

2.数论组合问题强调构造性思维与数学直觉，而非公式套用，显著降低模型通过“见过类似题”而直接作答的可能性；

3.空间推理任务依赖对二维/三维结构的内在建模，以文本片段呈现空间推理任务让大模型进行复杂求解。

# III. 排行榜
评测榜单：

| 模型名称                       | 准确率    |
|-------------------------------|----------|
| GPT-5-20250807                | 81       |
| Qwen3-235B-A22B-2507          | 79       |
| Grok-4-0709                   | 75       |
| GPT-oss-120b                  | 69       |
| Gemini2.5-Pro-0617            | 69       |
| GPT-5 mini                    | 68       |
| DeepSeek-V3.1                 | 68       |
| DeepSeek-R1-0528              | 67       |
| GPT-5-Chat-0807               | 65       |
| DeepSeek-V3-0324              | 64       |
| Gemini2.5-flash-0617          | 63       |
| Kimi-k2-Turbo                 | 60       |
| GLM-4.5                       | 56       |
| Llama 4 Maverick              | 45       |
| Ernie-4.5-424B-A47B           | 42       |


# IV. 联系我们
更多详情请登陆晓天衡宇大模型评测平台官网：https://skylenage.alibaba-inc.com/sla/home

联系我们：skylenage@service.alibaba.com





# I. Benchmark Introduction
SKYLENAGE-ReasoningMath (Reasoning Math Assessment) covers multi-level reasoning tasks from basic arithmetic to advanced mathematics, encompassing logical deduction, algebraic transformations, geometric analysis, probability and statistics, and other dimensions. It aims to assess a model's ability to understand, reason, and solve structured mathematical problems. The dataset design emphasizes problem difficulty grading and cognitive level division, supporting fine-grained ability assessment.

Dataset Introduction:

ReasoningMath.json is the data file, containing 100 open-source problems, including sequence numbers, difficulty levels, subject classifications, questions, and final solutions.

Selected Problem Appendix.xlsx is the solution appendix for selected problems, containing 30 open-source problems, including sequence numbers, thought chain analysis criteria, and problem-solving analysis criteria.

SKYLENAGE Technical Report.pdf is the technical report.

# II. Benchmark Features
The core goal of this benchmark is to overcome the limitations of current mainstream benchmarks, which emphasize computation over logic and results over process. We focus on three high-level reasoning tasks that are underrepresented in common training corpora and difficult to solve through memorization or pattern matching: intuitive logic, number theoretic combinatorics, and spatial reasoning. These three capabilities not only challenge the model's abstract thinking skills but also effectively mitigate typical issues found in existing benchmarks.

1. To address data contamination and memorization-based answering, we deliberately avoided high-frequency question types, selecting task types that are infrequent or even absent in online text. Intuitive logic tasks involve non-standardized multi-role and multi-constraint reasoning, with diverse formulations and unfixed solution paths, making them difficult to fully capture in training data.

2. Number theoretic combinatorics emphasize constructive thinking and mathematical intuition over formulaic application, significantly reducing the likelihood that models will simply answer based on "experienced" problems.

3. Spatial reasoning tasks rely on intrinsic modeling of two-dimensional/three-dimensional structures. Presenting spatial reasoning tasks in text snippets allows large models to solve complex problems.

# III. Rankings
Evaluation Rankings:

| Model Name | Accuracy |
|---------------------------|----------|
| GPT-5-20250807 | 81 |
| Qwen3-235B-A22B-2507 | 79 |
| Grok-4-0709 | 75 |
| GPT-oss-120b | 69 |
| Gemini2.5-Pro-0617 | 69 |
| GPT-5 mini | 68 |
| DeepSeek-V3.1 | 68 |
| DeepSeek-R1-0528 | 67 |
| GPT-5-Chat-0807 | 65 |
| DeepSeek-V3-0324 | 64 |
| Gemini2.5-flash-0617 | 63 |
| Kimi-k2-Turbo | 60 |
| GLM-4.5 | 56 |
| Llama 4 Maverick | 45 |
| Ernie-4.5-424B-A47B | 42 |

# IV. Contact Us
For more details, please visit the official website of the Xiaotian Hengyu Large Model Evaluation Platform: https://skylenage.alibaba-inc.com/sla/home

Contact us: skylenage@service.alibaba.com





