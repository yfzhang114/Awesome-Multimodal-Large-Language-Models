# Awesome-Multimodal-Large-Language-Models
his is a repository for organizing articles related to Multimodal Large Language Models, Large Language Models, and Diffusion Models; Most papers are linked to **my reading notes**. Feel free to visit my [personal homepage](https://yfzhang114.github.io/) and contact me for collaboration and discussion.


### About Me :high_brightness: 
I'm a third-year Ph.D. student at the State Key Laboratory of Pattern Recognition, the University of Chinese Academy of Sciences, advised by Prof. [Tieniu Tan](http://people.ucas.ac.cn/~tantieniu). I have also spent time at Microsoft, advised by Prof. [Jingdong Wang](https://jingdongwang2017.github.io/), alibaba DAMO Academy, work with Prof. [Rong Jin](https://scholar.google.com/citations?user=CS5uNscAAAAJ&hl=zh-CN).


###  🔥 Updated 2024-10-28
- Recent advanced Multimodal Large Language Models and Alignment Methods have been updated.
- Our benchmark  [MME-RealWorld](https://mme-realworld.github.io/) has been released, the most difficult and largest pure manual annotation image perception benchmark so far.  [[Code]](https://github.com/yfzhang114/MME-RealWorld) [[Reading Notes]](https://zhuanlan.zhihu.com/p/717129017)
- Our model  [SliME](https://arxiv.org/abs/2406.08487) has been released, a high-resolution MLLM that can also be extend to video analysis.  [[Code]](https://github.com/yfzhang114/SliME) [[Reading Notes]](https://zhuanlan.zhihu.com/p/703258020)
- Our paper  [Debiasing Multimodal Large Language Models](https://arxiv.org/abs/2403.05262) has been released.  [[Code]](https://github.com/yfzhang114/LLaVA-Align) [[Reading Notes]](https://zhuanlan.zhihu.com/p/686461442)

# Table of Contents (ongoing)
* [Multimodal Large Language Models](#multimodal-large-language-models)
* [BenchMark and Dataset](#benchmark-and-dataset)
* [Unify Multimodal Understanding and Generation](#unify-multimodal-understanding-and-generation)
* [Alignment With Human Preference (MLLM)](#alignment-with-human-preference-mllm)
* [Alignment With Human Preference (LLM)](#alignment-with-human-preference-llm)


# Survey and Outlook
1. [万字长文总结多模态大模型最新进展（Modality Bridging篇）](https://zhuanlan.zhihu.com/p/688215018)
2. [万字长文总结多模态大模型最新进展（Video篇）](https://zhuanlan.zhihu.com/p/704246896)
3. [Aligning Large Language Models with Human](https://zhuanlan.zhihu.com/p/693160839)

   
# Multimodal Large Language Models
1. [MM1.5: Methods, Analysis & Insights from Multimodal LLM Fine-tuning](https://zhuanlan.zhihu.com/p/900354617)(apple：多模态大模型炼丹指南)
2. [Building and better understanding vision-language models: insights and future directions](https://zhuanlan.zhihu.com/p/731680062)(Hugging Face：探索多模态大模型的最佳技术路线)
3. [Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution](https://arxiv.org/pdf/2409.12191)(精细的动态分辨率策略+多模态旋转位置嵌入)
4. [LongLLaVA: Scaling Multi-modal LLMs to 1000 Images Efficiently via Hybrid Architecture](https://huggingface.co/papers/2409.02889)(在单个A100 80GB GPU上可以处理近千张图像)
5. [MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?](https://zhuanlan.zhihu.com/p/717129017)(最难多模态Benchmark. QwenVL-2第一但未及格！)
6. [VITA: Towards Open-Source Interactive Omni Multimodal LLM](https://zhuanlan.zhihu.com/p/714031459)(VITA : 首个开源支持自然人机交互的全能多模态大语言模型)
7. [Beyond LLaVA-HD: Diving into High-Resolution Large Multimodal Models](https://github.com/yfzhang114/SliME)(高效处理高分辨率图像的多模态大模型)
8. [Matryoshka Multimodal Models](https://zhuanlan.zhihu.com/p/700906592)(如何在正确回答视觉问题的同时使用最少的视觉标记？)
9. [Chameleon: Mixed-Modal Early-Fusion Foundation Models](https://zhuanlan.zhihu.com/p/698911049)(meta: 所有模态都回到token regreesion以达到灵活的理解/生成)
10. [Flamingo: a Visual Language Model for Few-Shot Learning](https://zhuanlan.zhihu.com/p/688215018)(LLM每一层创建额外的block处理视觉信息)
11. [BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://zhuanlan.zhihu.com/p/688215018)(q-former融合视觉-语言信息)
12. [InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(qformer+instruction tuning)
13. [Visual Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(MLP对齐特征，gpt4v生成instruction tuning数据)
14. [Improved Baselines with Visual Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(对于llava数据集以及模型大小的初步scaling)
15. [LLaVA-NeXT: Improved reasoning, OCR, and world knowledge](https://zhuanlan.zhihu.com/p/688215018)(分辨率*4，数据集更大)
16. [Cheap and Quick: Efficient Vision-Language Instruction Tuning for Large Language Models](https://zhuanlan.zhihu.com/p/688215018)(一种端到端的优化方案，通过轻量级适配器连接图像编码器和LLM)
17. [MIMIC-IT: Multi-Modal In-Context Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)( MIMIC-IT包含多个图片或视频的输入数据，并支持多模态上下文信息)
18. [LLaVAR: Enhanced Visual Instruction Tuning for Text-Rich Image Understanding](https://zhuanlan.zhihu.com/p/688215018)(使用公开可用的OCR工具在LAION数据集的422K个文本丰富的图像上收集结果)
19. [SVIT: Scaling up Visual Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(一个包含420万个视觉指导调整数据点的数据集)
20. [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://zhuanlan.zhihu.com/p/688215018)(cross attention对齐特征，更大的第一阶段训练数据)
21. [NExT-GPT: Any-to-Any Multimodal LLM](https://zhuanlan.zhihu.com/p/688215018)(端到端通用的任意对任意MM-LLM（Multimodal-Large Language Model）系统)
22. [InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition](https://zhuanlan.zhihu.com/p/688215018)(视觉信息的压缩采样)
23. [CogVLM: Visual Expert for Pretrained Language Models](https://zhuanlan.zhihu.com/p/688215018)(在LLM的各层添加visual expert，它具有独立的QKV和FFN相关的参数)
24. [OtterHD: A High-Resolution Multi-modality Model](https://zhuanlan.zhihu.com/p/688215018)(专门设计用于以细粒度精度解释高分辨率视觉输入)
25. [Monkey : Image Resolution and Text Label Are Important Things for Large Multi-modal Models](https://zhuanlan.zhihu.com/p/688215018)(Monkey模型提出了一种有效地提高输入分辨率的方法，最高可达 896 x 1344 像素)
26. [LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models](https://zhuanlan.zhihu.com/p/688215018)(LLaMA-VID赋予现有框架支持长达一小时的视频，并通过额外的上下文标记推动了它们的上限)
27. [MoE-LLaVA: Mixture of Experts for Large Vision-Language Models](https://zhuanlan.zhihu.com/p/688215018)(解决了多模态稀疏学习中的性能下降问题)
28. [LLaVA-UHD: an LMM Perceiving Any Aspect Ratio and High-Resolution Images](https://zhuanlan.zhihu.com/p/688215018)(高效处理任何纵横比和高分辨率的图像)
29. [Yi-VL](https://zhuanlan.zhihu.com/p/688215018)(Yi-VL采用了LLaVA架构，经过全面的三阶段训练过程，以将视觉信息与Yi LLM的语义空间良好对齐：)
30. [Mini-Gemini](https://zhuanlan.zhihu.com/p/693063778)(双视觉编码器，使用低分辨率的视觉编码器特征作为query，将高分辨率特征作为key 和value进行token mining)
31. [Chat-UniVi: Unified Visual Representation Empowers Large Language Models with Image and Video Understanding](https://zhuanlan.zhihu.com/p/704246896)(采用了一组动态视觉tokens来统一表示图像和视频。使模型能够高效利用有限数量的视觉tokens，同时捕捉图像所需的空间细节和视频所需的全面时间关系。)
32. [VILA: On Pre-training for Visual Language Models](https://zhuanlan.zhihu.com/p/704246896)(交错的预训练数据是有益的，而单纯的图像-文本对并非最佳选择。)
33. [ST-LLM: Large Language Models Are Effective Temporal Learners](https://zhuanlan.zhihu.com/p/704246896)(ST-LLM提出了一种动态掩码策略，并设计了定制的训练目标。此外，针对特别长的视频，设计了一个全局-局部输入模块，以平衡效率和效果。)
34. [Video-LLaVA: Learning United Visual Representation by Alignment Before Projection](https://zhuanlan.zhihu.com/p/704246896)(用视频特有的encoder提升视频理解能力而非image encoder)

# BenchMark and Dataset
1. [MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?](https://zhuanlan.zhihu.com/p/717129017)(最难多模态Benchmark. QwenVL-2第一但未及格！)
2. [MMMU-Pro: A More Robust Multi-discipline Multimodal Understanding Benchmark](https://hub.baai.ac.cn/paper/baeaa2a4-4374-4cf3-927e-82df61ec3e8e)(MMMU的进阶版，更注重图像的感知对问题的影响)
3. [From Pixels to Prose: A Large Dataset of Dense Image Captions](https://arxiv.org/pdf/2406.10328)(1600万生成的image-text pair，利用尖端的视觉语言模型(Gemini 1.0 Pro Vision)进行详细和准确的描述。)
4. [ShareGPT4Video: Improving Video Understanding and Generation with Better Captions](https://zhuanlan.zhihu.com/p/704246896)(40k from gpt4-v, 4814k生成于自己训练的模型)
5. [OBELICS: An Open Web-Scale Filtered Dataset of Interleaved Image-Text Documents](https://arxiv.org/pdf/2306.16527)(141 million web pages extracted from Common Crawl, 353 million associated images, and 115 billion text tokens)
6. [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/abs/2306.14565)(在数据层面，以细粒度片段级更正的形式收集人类反馈；在方法层面，我们提出了密集直接偏好优化(DDPO))
7. [Multimodal Self-Instruct: Synthetic Abstract Image and Visual Reasoning Instruction Using Language Model](https://arxiv.org/abs/2407.07053)(在数据层面, 通过代码作为媒介合成抽象图表,并且 benchmarking 了当前多模态模型在抽象图的理解上的不足.)
# Unify Multimodal Understanding and Generation

1. [Chameleon: Mixed-Modal Early-Fusion Foundation Models](https://zhuanlan.zhihu.com/p/719475102)(“早期融合”的方法使得模型能够跨模态推理和生成真正的混合文档。)
2. [Show-o: One Single Transformer to Unify Multimodal Understanding and Generation](https://zhuanlan.zhihu.com/p/719475102)(文本作为离散标记进行自回归建模，而连续图像像素则使用去噪扩散建模。)
3. [Transfusion: Predict the Next Token and Diffuse Images with One Multi-Modal Model](https://zhuanlan.zhihu.com/p/719475102)(采用了文本的下一个标记预测和图像的扩散作为目标函数,型在不增加计算成本的前提下，实现了更好的模态整合与生成效果。)
4. [VILA-U: a Unified Foundation Model Integrating Visual Understanding and Generation](https://zhuanlan.zhihu.com/p/785607305)(清华&MIT：统一视频理解与生成)
5. [MoMa: Efficient Early-Fusion Pre-training with Mixture of Modality-Aware Experts](https://zhuanlan.zhihu.com/p/858555788)(META:MOE是混合模态理解/生成的最佳选择)
6. [MIO: A Foundation Model on Multimodal Tokens](https://zhuanlan.zhihu.com/p/2186671721)(01AI: 四模态理解/生成大一统)
7. [Harmonizing Visual Text Comprehension and Generation](https://arxiv.org/abs/2407.16364)()
# Alignment With Human Preference (MLLM)
1. [Aligning Large Multimodal Models with Factually Augmented RLHF](https://llava-rlhf.github.io/)
2. [CLIP-DPO: Vision-Language Models as a Source of Preference for Fixing Hallucinations in LVLMs](https://www.arxiv.org/abs/2408.10433)(使用预训练的 CLIP 模型对 LVLM 自生成的标题进行排序，以构建 DPO 的正负对)
3. [ODE: Open-Set Evaluation of Hallucinations in Multimodal Large Language Models](https://www.arxiv.org/abs/2409.09318)(选择了一种动态生成方法来创建一个 open-set benchmark，引入了开放集动态评估协议(ODE)，专门用于评估 MLLM 中的对象存在幻觉)
4. [Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization](https://arxiv.org/abs/2311.16839)(本文将消除幻觉视为一种模型偏好，使模型偏向于无幻觉输出，于是提出了一种对幻觉敏感的多模态DPO 策略 —— HA-DPO。我们还引入了句子级幻觉比率(SHR)，它不受固定类别和范围的限制，为多模态幻觉提供了广泛、细粒度和定量的测量)
5. [Detecting and Preventing Hallucinations in Large Vision Language Models](https://arxiv.org/abs/2308.06394)(为了便于自动检测幻觉，我们首先使用 InstructBLIP 的 VQA 响应构建了一个多样化的人工标记数据集 M-HalDetect，专注于在详细图像描述的子句级别上进行细粒度注释。在这个数据集上训练不同密度(句子级，子句子级)的多个奖励模型，用于幻觉检测。我们也使用细粒度直接偏好优化(FDPO)直接优化 InstructBLIP)
6. [RLAIF-V: Aligning MLLMs through Open-Source AI Feedback for Super GPT-4V Trustworthiness](https://arxiv.org/abs/2405.17220)(同一个大模型生成多个回复，将回复按句拆分，之后转化为问句让开源模型回复准确度，将所有准确度相加，得到偏好数据，用于迭代DPO)
7. [Enhancing Visual-Language Modality Alignment in Large Vision Language Models via Self-Improvement](https://arxiv.org/abs/2405.15973)(我们提出了 Self-Improvement Modality Alignment(SIMA)，旨在通过自我完善机制进一步改善 LVLM 内视觉模态和语言模态之间的对齐)

# Alignment With Human Preference (LLM)

1. [ChatGLM-Math：Improving Math Problem-Solving in Large Language Models with a Self-Critique Pipeline](https://zhuanlan.zhihu.com/p/698983475)(ChatGLM-Math: Self-Critique迭代对齐显著提升数学能力)
2. [Beyond One-Preference-Fits-All Alignment: Multi-Objective Direct Preference Optimization](https://zhuanlan.zhihu.com/p/698782623)(大语言模型的多目标对齐)
3. [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://zhuanlan.zhihu.com/p/693163438)(直接偏好优化克服RLHF不稳定的问题)
4. [KTO: Model Alignment as Prospect Theoretic Optimization](https://zhuanlan.zhihu.com/p/693163438)(不需要成对数据的偏好优化)
5. [Direct Preference Optimization with an Offset](https://zhuanlan.zhihu.com/p/693163438)(带偏移的DPO, 要求首选响应和不受欢迎响应之间的可能性差异大于一个偏移值)
6. [Contrastive preference learning: Learning from human feedback without reinforcement learning](https://zhuanlan.zhihu.com/p/693163438)(对比偏好学习（CPL）算法，该算法用于从偏好中学习最优策略而无需学习奖励函数，从而避免了对RL的需求)
7. [Statistical Rejection Sampling Improves Preference Optimization](https://zhuanlan.zhihu.com/p/693163438)(使用拒绝抽样从目标最优策略中获取偏好数据，从而更准确地估计最优策略)
8. [Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study](https://zhuanlan.zhihu.com/p/693163438)(在所有实验中，PPO始终优于DPO。特别是在最具挑战性的代码竞赛任务中，PPO实现了最先进的结果)
9. [Fine-tuning Aligned Language Models Compromises Safety](https://zhuanlan.zhihu.com/p/696707347)(微调对齐的语言模型会损害安全性)
10. [ChatGLM-Math: Improving Math Problem-Solving in Large Language Models with a Self-Critique Pipeline](https://mp.weixin.qq.com/s/lg7ueR9b-om0ecUEoT4x8w)(reward model, Rejective Fine-tuning, then DPO迭代提升模型数学性能)
11. [SimPO: Simple Preference Optimization with a Reference-Free Reward](https://zhuanlan.zhihu.com/p/700438956)(length reg+去掉ref model)
12. [towards analyzing and understanding the limitations of dpo: a theoretical perspective](https://zhuanlan.zhihu.com/p/701213691)(DPO的实际优化过程对SFT后的LLMs对齐能力的初始条件为什么敏感)
13. [Iterative Length-Regularized Direct Preference Optimization: A Case Study on Improving 7B Language Models to GPT-4 Level](https://arxiv.org/abs/2406.11817)(表明迭代 DPO (iDPO)可以通过精心设计将 7B 模型的 LC win rate 增强到 GPT-4 水平)
14. [Step-DPO: Step-wise Preference Optimization for Long-chain Reasoning of LLMs](https://arxiv.org/abs/2406.18629)(出了一种有效且经济的 pipeline 来收集成对数学问题偏好数据。引入了 Step-DPO，最大化下一个推理步骤正确的概率，最小化其错误的概率)
