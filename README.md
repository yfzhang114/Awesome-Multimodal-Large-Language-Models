# Awesome-Multimodal-Large-Language-Models
his is a repository for organizing articles related to Multimodal Large Language Models, Large Language Models, and Diffusion Models; Most papers are linked to **my reading notes**. Feel free to visit my [personal homepage](https://yfzhang114.github.io/) and contact me for collaboration and discussion.


### About Me :high_brightness: 
I'm a third-year Ph.D. student at the State Key Laboratory of Pattern Recognition, the University of Chinese Academy of Sciences, advised by Prof. [Tieniu Tan](http://people.ucas.ac.cn/~tantieniu). I have also spent time at Microsoft, advised by Prof. [Jingdong Wang](https://jingdongwang2017.github.io/), alibaba DAMO Academy, work with Prof. [Rong Jin](https://scholar.google.com/citations?user=CS5uNscAAAAJ&hl=zh-CN).


###  🔥 Updated 2024-03-30
- Recent Modality Bridging papers of Multimodal Large Language Models have been updated.
- Our paper  [Debiasing Multimodal Large Language Models](https://arxiv.org/abs/2403.05262) has been released.  [[Code]](https://github.com/yfzhang114/LLaVA-Align) [[Reading Notes]](https://zhuanlan.zhihu.com/p/686461442)

# Table of Contents (ongoing)
* [Multimodal Large Language Models](#multimodal-large-language-models)
* [Diffusion Models](#diffusion-models)
* [Hallucination](#hallucination)
* [Alignment With Human Preference](#alignment-with-human-preference)
# Multimodal Large Language Models

1. [Chameleon: Mixed-Modal Early-Fusion Foundation Models](https://zhuanlan.zhihu.com/p/698911049)(meta: 所有模态都回到token regreesion以达到灵活的理解/生成)
2. [Flamingo: a Visual Language Model for Few-Shot Learning](https://zhuanlan.zhihu.com/p/688215018)(LLM每一层创建额外的block处理视觉信息)
3. [BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://zhuanlan.zhihu.com/p/688215018)(q-former融合视觉-语言信息)
4. [InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(qformer+instruction tuning)
5. [Visual Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(MLP对齐特征，gpt4v生成instruction tuning数据)
6. [Improved Baselines with Visual Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(对于llava数据集以及模型大小的初步scaling)
7. [LLaVA-NeXT: Improved reasoning, OCR, and world knowledge](https://zhuanlan.zhihu.com/p/688215018)(分辨率*4，数据集更大)
8. [Cheap and Quick: Efficient Vision-Language Instruction Tuning for Large Language Models](https://zhuanlan.zhihu.com/p/688215018)(一种端到端的优化方案，通过轻量级适配器连接图像编码器和LLM)
9. [MIMIC-IT: Multi-Modal In-Context Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)( MIMIC-IT包含多个图片或视频的输入数据，并支持多模态上下文信息)
10. [LLaVAR: Enhanced Visual Instruction Tuning for Text-Rich Image Understanding](https://zhuanlan.zhihu.com/p/688215018)(使用公开可用的OCR工具在LAION数据集的422K个文本丰富的图像上收集结果)
11. [SVIT: Scaling up Visual Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(一个包含420万个视觉指导调整数据点的数据集)
12. [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://zhuanlan.zhihu.com/p/688215018)(cross attention对齐特征，更大的第一阶段训练数据)
13. [NExT-GPT: Any-to-Any Multimodal LLM](https://zhuanlan.zhihu.com/p/688215018)(端到端通用的任意对任意MM-LLM（Multimodal-Large Language Model）系统)
14. [InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition](https://zhuanlan.zhihu.com/p/688215018)(视觉信息的压缩采样)
15. [CogVLM: Visual Expert for Pretrained Language Models](https://zhuanlan.zhihu.com/p/688215018)(在LLM的各层添加visual expert，它具有独立的QKV和FFN相关的参数)
16. [OtterHD: A High-Resolution Multi-modality Model](https://zhuanlan.zhihu.com/p/688215018)(专门设计用于以细粒度精度解释高分辨率视觉输入)
17. [Monkey : Image Resolution and Text Label Are Important Things for Large Multi-modal Models](https://zhuanlan.zhihu.com/p/688215018)(Monkey模型提出了一种有效地提高输入分辨率的方法，最高可达 896 x 1344 像素)
18. [LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models](https://zhuanlan.zhihu.com/p/688215018)(LLaMA-VID赋予现有框架支持长达一小时的视频，并通过额外的上下文标记推动了它们的上限)
19. [MoE-LLaVA: Mixture of Experts for Large Vision-Language Models](https://zhuanlan.zhihu.com/p/688215018)(解决了多模态稀疏学习中的性能下降问题)
20. [LLaVA-UHD: an LMM Perceiving Any Aspect Ratio and High-Resolution Images](https://zhuanlan.zhihu.com/p/688215018)(高效处理任何纵横比和高分辨率的图像)
21. [Yi-VL](https://zhuanlan.zhihu.com/p/688215018)(Yi-VL采用了LLaVA架构，经过全面的三阶段训练过程，以将视觉信息与Yi LLM的语义空间良好对齐：)
22. [Mini-Gemini](https://zhuanlan.zhihu.com/p/693063778)(双视觉编码器，使用低分辨率的视觉编码器特征作为query，将高分辨率特征作为key 和value进行token mining)

# Diffusion Models

# Hallucination

# Alignment With Human Preference

1. [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://zhuanlan.zhihu.com/p/693163438)(直接偏好优化克服RLHF不稳定的问题)
2. [KTO: Model Alignment as Prospect Theoretic Optimization](https://zhuanlan.zhihu.com/p/693163438)(不需要成对数据的偏好优化)
3. [Direct Preference Optimization with an Offset](https://zhuanlan.zhihu.com/p/693163438)(带偏移的DPO, 要求首选响应和不受欢迎响应之间的可能性差异大于一个偏移值)
4. [Contrastive preference learning: Learning from human feedback without reinforcement learning](https://zhuanlan.zhihu.com/p/693163438)(对比偏好学习（CPL）算法，该算法用于从偏好中学习最优策略而无需学习奖励函数，从而避免了对RL的需求)
5. [Statistical Rejection Sampling Improves Preference Optimization](https://zhuanlan.zhihu.com/p/693163438)(使用拒绝抽样从目标最优策略中获取偏好数据，从而更准确地估计最优策略)
6. [Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study](https://zhuanlan.zhihu.com/p/693163438)(在所有实验中，PPO始终优于DPO。特别是在最具挑战性的代码竞赛任务中，PPO实现了最先进的结果)
7. [Fine-tuning Aligned Language Models Compromises Safety](https://zhuanlan.zhihu.com/p/696707347)(微调对齐的语言模型会损害安全性)
8. [ChatGLM-Math: Improving Math Problem-Solving in Large Language Models with a Self-Critique Pipeline](https://mp.weixin.qq.com/s/lg7ueR9b-om0ecUEoT4x8w)(reward model, Rejective Fine-tuning, then DPO迭代提升模型数学性能)
