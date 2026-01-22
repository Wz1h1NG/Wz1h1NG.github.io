---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<script type="text/javascript">
	$(document).ready(function() {
		$('a[href^="http"]').each(function() {
			$(this).attr('target', '_blank');
		});
	});
</script>

<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

<p style="text-align:justify; text-justify:inter-ideograph;">
     I am currently an Associate Professor (Tenured) of computer science at Great Bay University, 国家优青(海外), leading the YU Vision (YUV) Group.
     I was a Postdoctoral researcher at ROSE Lab, Nanyang Technological University, working with <a href="https://scholar.google.com/citations?user=UGZXLxIAAAAJ&hl=en" target="_blank">Prof. Alex Kot</a>.
     I also serve as an advisor on rPPG-based healthcare for <a href="https://www.biotrillion.com/team" target="_blank">BioTrillion</a>, USA.
     I received my PhD degree in CS at CMVS, University of Oulu in 2022 (supervised by <a href="https://scholar.google.com/citations?user=hzywrFMAAAAJ&hl=en" target="_blank">Prof. Guoying Zhao</a>).
     I was a visiting scholar at TVG, University of Oxford, from July to November 2021, supervised by <a href="https://scholar.google.com/citations?user=kPxa2w0AAAAJ&hl=en" target="_blank">Prof. Philip Torr</a>.
     My research interests include computer vision, biometric security, and multimodal learning.
</p>

<span class='anchor' id='research'></span>
<span class='anchor' id='join-us'></span>

<p style="text-align:justify; text-justify:inter-ideograph;">
    <font color="a82e2e"><b>[Urgent Recruitment:]</b> I am recruiting PostDoc (45W/year) and 特任研究员 (35W/year) and Research Assistant (Excellent master student) to join my research team. 
    For prospective collaborators, please email me with your CV and research plan. 每年招收湾大-深大/南科大联培硕士，湾大-哈工深联培博士若干.</font>
</p>

<span class='anchor' id='updates'></span>
# News
- [2026.01] We organize the [2nd Workshop & Challenge on Subtle Visual Computing (SVC)](https://sites.google.com/view/svc-cvpr26) @ CVPR 2026. Welcome to participate!
- [2025.12] Two papers on facial AU detection and fine-grained recognition are accepted by IEEE TIP and TMM
- [2025.11] Six papers on VLA/audio-visual/face anti-spoofing/action recognition are accepted by AAAI'26 (3 Oral)
- [2025.08] One paper on continual face anti-spoofing is accepted by IEEE TPAMI
- [2025.08] Awarded as 2025 GDSIG Science and Technology Progress First Prize (广东省图象图形学会科技进步一等奖，序1)
- [2025.07] Five papers are accepted by ACM MM 2025
- [2025.06] Two papers on face anti-spoofing and adversarial attack are accepted by ICCV 2025; two papers on face anti-spoofing are accepted by IEEE TIFS
- [2025.05] One paper on audio-visual MLLM is accepted by IEEE TPAMI
- [2025.05] One paper on multimodal face anti-spoofing is accepted by IEEE TPAMI
- [2025.05] Our paper [FusionMamba](https://link.springer.com/article/10.1007/s44267-024-00072-9) is selected as the first [Cover Article (首个封面文章) of the Visual Intelligence](https://mp.weixin.qq.com/s/R1MAioNzp8Kpqm6Lyiffgw) journal!

<a onclick="toggleList()" id='more'>Show more</a>
<div id="hiddenList" style="display:none;">
  {% capture hidden_list %}
  - [2025.04] One paper on multimodal fake news detection is accepted by IJCAI 2025
  - [2025.04] Will serve as Area Chair (AC) for ACM MM 2025 and BMVC 2025; Promote as CCF Senior Member
  - [2025.03] We organize the [1st Workshop & Challenge on Subtle Visual Computing (SVC)](https://sites.google.com/view/svc-mm25) @ ACM MM 2025. Welcome to participate!
  - [2025.02] Two papers on video understanding and AIGC are accepted by CVPR 2025
  - [2025.02] Call for Papers: Special Issue on [Subtle Visual Computing, Machine Intelligence Research](https://link.springer.com/journal/11633/updates/27737746) (IF 6.4, JCR Q1区)
  - [2025.01] One paper on video understanding is accepted by ICLR 2024; One paper on camouflaged object detection is accepted by IEEE TIP
  - [2024.11] Our PhysMamba paper is granted [CCBR 2024 Best Paper Honorable Mention Award (最佳论文提名奖)](https://drive.google.com/file/d/1DnuEuENHoEvMs2G6PwrRnq37ArajycrC/view?usp=sharing), Congra. to Chaoqi & Yiping！
  - [2024.07] Our paper is awarded as the [Best Paper Candidate (最佳论文提名)](https://drive.google.com/file/d/1iaYTAUyUO_t7lfUldZ9V3TPZOY88YrRS/view?usp=drive_link) of [ICME 2024](https://2024.ieeeicme.org/awards/)
  - [2024.07] One paper on manipulation detection is accepted by Cell Patterns; One paper on multimedia privacy is accepted by ACM MM 2024
  - [2024.05] Organizing IJCB'24 Special Session '[Multimodal Human Behavior Understanding and Generation (MUG)](https://sites.google.com/view/ijcb-mug2024)'
  - [2024.02] Promoted to IEEE Senior Member
  - [2023.12] Our CCBR'23 paper '[Detect Any Deepfake](https://github.com/laiyingxin2/DADF)' is granted IAPR Best Student Paper Award, Congra. to Yingxin！
  - [2023.10] Elected among World's Top 2% Scientists 2023 by Stanford University (入选2023全球前2%顶尖科学家榜单)
  - [2023.01] Invited keynote talk for [WACV2023 - Workshop on Manipulation, Adversarial, and Presentation Attacks in Biometrics](https://sites.google.com/view/wacv2023-map-a/home)
  {% endcapture %}
  {{ hidden_list | markdownify }}
</div>
<a onclick="toggleList()" id='less' style='display:none;'>Show less</a>
<script>
function toggleList() {
    var list = document.getElementById('hiddenList');
    list.style.display = list.style.display === 'none' ? 'block' : 'none';
    var button = document.getElementById('more');
    button.style.display = button.style.display === 'none' ? 'block' : 'none';
    var buttom_less = document.getElementById('less');
    buttom_less.style.display = buttom_less.style.display === 'none' ? 'block' : 'none';
}
</script>


<span class='anchor' id='publications'></span>
# Publications
( # equal contribution, * corresponding author)

## Book Chapter
- [2] **Zitong Yu**, Chenxu Zhao and Zhen Lei. "**Face Presentation Attack Detection**". Handbook of Face Recognition (3rd Ed.), 2023
- [1] **Zitong Yu**, Jukka Komulainen, Xiaobai Li, and Guoying Zhao. "**Review of Face Presentation Attack Detection Competitions**." Handbook of Biometric Anti-Spoofing (3rd Ed.), Springer, 2023

## Journals
- [38] Kaishen Yuan#, **Zitong Yu#***, Xin Liu*, Bohao Xing, Yuting Zhang, Weicheng Xie, Linlin Shen, Bjorn W. Schuller. "**Multi-granularity Facial Emotional Representation with Unlabeled Data and Textual Supervision**", IEEE Transactions on Image Processing (TIP), 2026
- [37] Qiaoqi Li, Shuo Ye*, Yunfeng Diao, Dan Guo, Yantao Wei, Shutao Xia, **Zitong Yu***. "**CNIE: Content-Aware Non-Transferable Information Extraction for Fine-Grained Visual Categorization**", IEEE Transactions on Multimedia (TMM), 2026
- [36] Taorui Wang, Xun Lin, Yong Xu*, Qilang Ye, Dan Guo, Sergio Escalera, Ghada Khoriba, **Zitong Yu***. "**Micro-Gesture Recognition: A Comprehensive Survey of Datasets, Methods, and Challenges**", Machine Intelligence Research (MIR), 2025
- [35] Jiayu Zhang, Xun Lin, Jiajian Huang, Shuo Ye, Xiaobao Guo, Dongliang Zhu, Ruimin Hu, Dan Guo, Yanyan Liang, **Zitong Yu*** and Xiaochun Cao. "**Multimodal Deception Detection: A Survey**", Machine Intelligence Research (MIR), 2025
- [34] 郭园方#，**余梓彤#**，刘艾杉#，周文柏#，乔通#，李斌，张卫明，康显贵，周琳娜，俞能海，黄继武. "**多模态大模型安全研究进展**", 中国图象图形学报，2025年30卷第6期，2051-2081页, 2025
- [33] Zewen Li, **Zitong Yu***, Qilang Ye, Weicheng Xie, Wei Zhuo, Linlin Shen*. "**IAD-GPT: Advancing Visual Knowledge in Multimodal Large Language Model for Industrial Anomaly Detection**", IEEE Transactions on Instrumentation and Measurement (TIM), 2025
- [32] Yiping Xie, **Zitong Yu***, Bingjie Wu, Weicheng Xie*, Linlin Shen. "**SFDA-rPPG: Source-Free Domain Adaptive Remote Physiological Measurement with Spatio-Temporal Consistency**", IEEE Transactions on Instrumentation and Measurement (TIM), 2025
- [31] Rizhao Cai, Yawen Cui, **Zitong Yu***, Xun Lin, Changsheng Chen, Alex Kot. "**Rehearsal-Free and Efficient Continual Learning for Cross-Domain Face Anti-Spoofing**", IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2025
- [30] Daiyuan Li#, **Zitong Yu#**, Jinwu Hu, Guohao Chen, Jinghui Zeng, Mingkui Tan*. "**Fine-Grained Textual Guidance for Generalized Multi-Modal Face Anti-Spoofing**", IEEE Transactions on Information Forensics and Security (TIFS), 2025
- [29] Jingyi Yang, **Zitong Yu***, Jia He, Xiuming Ni, Liepiao Zhang, Hui Li*, Xiaochun Cao. "**G2V2former: Graph Guided Video Vision Transformer for Face Anti-Spoofing**", IEEE Transactions on Information Forensics and Security (TIFS), 2025
- [28] Qilang Ye#, **Zitong Yu#***, Rui Shao, Yawen Cui, Xiangui Kang, Xin Liu, Philip Torr, Xiaochun Cao. "**CAT+: Investigating and Enhancing Audio-visual Understanding in Large Language Models**", IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2025
- [27] Xun Lin, Ajian Liu, **Zitong Yu***, Rizhao Cai, Shuai Wang, Yi Yu, Jun Wan, Zhen Lei, Xiaochun Cao, Alex Kot. "**Reliable and Balanced Transfer Learning for Generalized Multimodal Face Anti-Spoofing**", IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2025
- [26] Yaning Zhang, Tianyi Wang, **Zitong Yu***, Zan Gao*, Linlin Shen, Shengyong Chen. "**MFCLIP: Multi-modal Fine-grained CLIP for Generalizable Diffusion Face Forgery Detection**", IEEE Transactions on Information Forensics and Security (TIFS), 2025
- [25] Bingjie Wu, **Zitong Yu***, Yiping Xie, Wei Liu, Chaoqi Luo, Yong Liu, Rick Siow Mong Goh. "**Semi-rPPG: Semi-Supervised Remote Physiological Measurement with Curriculum Pseudo-Labeling**", IEEE Transactions on Instrumentation and Measurement (TIM), 2025
- [24] Yichen Shi#, Yuhao Gao#, Yingxin Lai#, Hongyang Wang, Jun Feng, Lei He, Jun Wan, Changsheng Chen, **Zitong Yu***, and Xiaochun Cao. "**SHIELD: An evaluation benchmark for face spoofing and forgery detection with multimodal large language models**", Visual Intelligence, 2025
- [23] Chao Hao#, **Zitong Yu#***, Xin Liu*, Jun Xu, Huanjing Yue, and Jingyu Yang. "**A Simple yet Effective Network based on Vision Transformer for Camouflaged Object and Salient Object Detection**", IEEE Transactions on Image Processing (TIP), 2025
- [22] Xinyu Xie, Yawen Cui, Tao Tan, Xubin Zheng, and **Zitong Yu***. "**FusionMamba: Dynamic Feature Enhancement for Multimodal Image Fusion with Mamba**", Visual Intelligence, 2024
- [21] Ya Gao#, Jing Yang#, Minghui Wu, Chenxu Zhao, Anyang Su, Jie Song*, and **Zitong Yu***. "**DTIA: Disruptive Text-Image Alignment for Countering Text-to-Image Diffusion Model Personalization**", Data Science and Engineering, 2024
- [20] **Zitong Yu#**, Rizhao Cai#, Yawen Cui, Ajian Liu, and Changsheng Chen*. "**Visual Prompt Flexible-Modal Face Anti-Spoofing**", IEEE Transactions on Dependable and Secure Computing (TDSC), 2024
- [19] Yaning Zhang#, **Zitong Yu#**, Xiaobin Huang, Linlin Shen, and Jianfeng Ren. "**GenFace: A Large-Scale Fine-Grained Face Forgery Benchmark and Cross Appearance-Edge Learning**", IEEE Transactions on Information Forensics and Security (TIFS), 2024
- [18] Xun Lin, Wenzhong Tang, Haoran Wang, Yizhong Liu, Yakun Ju, Shuai Wang* and **Zitong Yu***. "**Exposing Image Splicing Traces in Scientific Publications via Uncertainty-guided Refinement**". Patterns, Cell, 2024
- [17] Rizhao Cai, **Zitong Yu***, Chenqi Kong, Haoliang Li, Changsheng Chen, Yongjian Hu and Alex Kot. "**S-Adapter: Generalizing Vision Transformer for Face Anti-Spoofing with Statistical Tokens**". IEEE Transactions on Information Forensics and Security (TIFS), 2024
- [16] Daiyuan Li, Guo Chen, Xixian Wu, **Zitong Yu*** and Mingkui Tan*. "**Cross-stage relation extraction and presentation attack material perception for face anti-spoofing**". Neural Networks, 2024
- [15] **Zitong Yu**, Rizhao Cai, Yawen Cui, Xin Liu, Yongjian Hu and Alex Kot. "**Rethinking Vision Transformer and Masked Autoencoder in Multimodal Face Anti-Spoofing**". International Journal of Computer Vision (IJCV), 2024
- [14] Xin Liu, Yuting Zhang, **Zitong Yu***, Hao Lu, Huanjing Yue and Jingyu Yang*. "**rPPG-MAE: Self-supervised Pre-training with Masked Autoencoders for Remote Physiological Measurement**". IEEE Transactions on Multimedia (TMM), 2024
- [13] **Zitong Yu**, Rizhao Cai, Zhi Li, Wenhan Yang, Jingang Shi, and Alex C Kot. "**Benchmarking Joint Face Spoofing and Forgery Detection with Visual and Physiological Cues**". IEEE Transactions on Dependable and Secure Computing (TDSC), 2024
- [12] **Zitong Yu**, Yuming Shen, Jingang Shi, Hengshuang Zhao, Yawen Cui, Jiehua Zhang, Philip Torr and Guoying Zhao. "**PhysFormer++: Facial Video-based Physiological Measurement with SlowFast Temporal Difference Transformer**". International Journal of Computer Vision (IJCV), 2023
- [11] Zezheng Wang#, **Zitong Yu#**, Xun Wang, Yunxiao Qin, Jiahong Li, Chenxu Zhao, Zhen Lei, Xin Liu, Size Li and Zhongyuan Wang. "**Consistency Regularization for Deep Face Anti-Spoofing**", IEEE Transactions on Information Forensics and Security (TIFS), 2022
- [10] **Zitong Yu**, Yunxiao Qin, Xiaobai Li, Chenxu Zhao, Zhen Lei, and Guoying Zhao. "**Deep Learning for Face Anti-Spoofing: A Survey**", IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2022
- [9] Ajian Liu#, Chenxu Zhao#, **Zitong Yu#**, Jun Wan, Anyang Su, Xing Liu, Zichang Tan, Sergio Escalera, Junliang Xing, Yanyan Liang, Guodong Guo, Zhen Lei, Stan Z Li, and Du Zhang. "**Contrastive context-aware learning for 3d high-fidelity mask face presentation attack detection**", IEEE Transactions on Information Forensics and Security (TIFS), 2022
- [8] Mingxin Liu, Jiong Mu*, **Zitong Yu***, Kun Ruan, Baiyi Shu, and Jie Yang. "**Adversarial learning and decomposition-based domain generalization for face anti-spoofing**." Pattern Recognition Letters (PRL), 2021
- [7] **Zitong Yu***, Xiaobai Li*, and Guoying Zhao. "**Facial Video-based Physiological Signal Measurement: Recent Advances and Affective Applications**." IEEE Signal Processing Magazine (SPM), 2021
- [6] Yunxiao Qin, **Zitong Yu**, Longbin Yan, Zezheng Wang, Chenxu Zhao, and Zhen Lei. "**Meta-Teacher For Face Anti-Spoofing**." IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2021
- [5] **Zitong Yu**, Xiaobai Li, Pichao Wang, and Guoying Zhao. "**TransRPPG: Remote Photoplethysmography Transformer for 3d Mask Face Presentation Attack Detection**." IEEE Signal Processing Letters (SPL), 2021
- [4] **Zitong Yu#**, Benjia Zhou#, Jun Wan, Pichao Wang, Haoyu Chen, Xin Liu, Stan Z Li, and Guoying Zhao. "**Searching Multi-Rate and Multi-Modal Temporal Enhanced Networks for Gesture Recognition**." IEEE Transactions on Image Processing (TIP), 2021
- [3] **Zitong Yu**, Xiaobai Li, Jingang Shi, Zhaoqiang Xia, and Guoying Zhao. "**Revisiting Pixel-Wise Supervision for Face Anti-Spoofing**." IEEE Transactions on Biometrics, Behavior, and Identity Science (TBIOM), 2021
- [2] **Zitong Yu**, Jun Wan, Yunxiao Qin, Xiaobai Li, Stan Z. Li, and Guoying Zhao. "**NAS-FAS: Static-Dynamic Central Difference Network Search for Face Anti-Spoofing**." IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2020
- [1] **Zitong Yu**, Xiaobai Li, Xuesong Niu, Jingang Shi, and Guoying Zhao. "**AutoHR: A Strong End-to-end Baseline for Remote Heart Rate Measurement with Neural Searching**." IEEE Signal Processing Letters, 2020

## Conferences
- [44] Yingjie Ma, Xun Lin, Yong Xu, Weicheng Xie, **Zitong Yu***. "**PA-FAS: Towards Interpretable and Generalizable Multimodal Face Anti-Spoofing via Path-Augmented Reinforcement Learning**", AAAI 2026 Oral
- [43] Hongyang Wang, Yichen Shi, Zhuofu Tao, Yuhao Gao, Liepiao Zhang, Xun Lin, Jun Feng, Xiaochen Yuan, **Zitong Yu***, Xiaochun Cao. "**FaceShield : Explainable Face Anti-Spoofing with Multimodal Large Language Models**", AAAI 2026
- [42] Qilang Ye, Yu Zhou*, Lian He, Jie Zhang, xuanming guo, Jiayu Zhang, Mingkui Tan, Weicheng Xie, Yue Sun, Tao Tan, Xiaochen Yuan, Ghada Khoriba, **Zitong Yu***. "**SUGAR: Learning Skeleton Representation with Visual-Motion Knowledge for Action Recognition**", AAAI 2026 Oral
- [41] Qilang Ye, Wei Zeng, Meng Liu*, Jie Zhang, Yupeng Hu, **Zitong Yu***, Yu Zhou. "**When Eyes and Ears Disagree: Can MLLMs Discern Audio-Visual Confusion?**", AAAI 2026
- [40] Yijie Zhu, Rui Shao*, Ziyang Liu, Jie He, Jizhihui Liu, Jiuru Wang, **Zitong Yu***. "**H-GAR: A Hierarchical Interaction Framework via Goal-Driven Observation-Action Refinement for Robotic Manipulation**", AAAI 2026 Oral
- [39] Chao Hao, Zezheng Wang*, Yanhua Huang, Ruiwen Xu, Wenzhe Niu, Xin Liu, **Zitong Yu***. "**Dynamic Collaboration of Multi-Language Models based on Minimal Complete Semantic Units**", EMNLP 2025
- [38] Yingxin Lai, Wang Hongyang, Jing yang, Xiangui Kang, Bin Li, Linlin Shen, **Zitong Yu***. "**GM-DF: Generalized Multi-Scenario Deepfake Detection**", ACM MM 2025
- [37] Yijie Zhu, Yibo Lyu, **Zitong Yu***, Rui Shao*, Kaiyang Zhou, Liqiang Nie. "**EmoSym: A Symbiotic Framework for Unified Emotional Understanding and Generation via Latent Reasoning**", ACM MM 2025
- [36] Xinqi Su, **Zitong Yu***, Yawen Cui, Ajian Liu, Xun Lin, Yuhao Wang, Haochen Liang, Wenhui Li, Li Shen, Xiaochun Cao. "**Dynamic Analysis and Adaptive Discriminator for Fake News Detection**", ACM MM 2025
- [35] Weicheng Xie, Chunlin Yan, Siyang Song, **Zitong Yu**, Linlin Shen, Laizhong Cui. "**Smooth Online Multiple Appropriate Facial Reaction Generation**", ACM MM 2025
- [34] Zhuozhao Hu, Kaishen Yuan, Xin Liu, **Zitong Yu**, Yuan Zong, Jingang Shi, Huanjing Yue, Jingyu Yang. "**FEALLM: Advancing Facial Emotion Analysis in Multimodal Large Language Models with Emotional Synergy and Reasoning**", ACM MM 2025
- [33] Jingyi Yang#, Xun Lin#, **Zitong Yu***, Liepiao Zhang, Xin Liu, Hui Li, Xiaochen Yuan, Xiaochun Cao. "**DADM: Dual Alignment of Domain and Modality for Face Anti-Spoofing**", ICCV 2025
- [32] Zenghao Niu, Weicheng Xie, Siyang Song, **Zitong Yu**, Feng Liu, Linlin Shen. "**Enhancing Adversarial Transferability by Balancing Exploration and Exploitation with Gradient-Guided Sampling**", ICCV 2025
- [31] Ye Zhu, Yunan Wang, **Zitong Yu***. "**Multimodal Fake News Detection: MFND Dataset and Shallow-Deep Multitask Learning**", IJCAI 2025
- [30] Rong Gao, Xin Liu, Zhuozhao Hu, Bohao Xing, Baiqiang Xia, **Zitong Yu**, Heikki Kälviäinen. "**FSBench: A Figure Skating Benchmark for Advancing Artistic Sports Understanding**", CVPR 2025
- [29] Yanfeng Li, Ka-Hou Chan, Yue Sun, Chan-Tong Lam, Tong Tong, **Zitong Yu**, Keren Fu, Xiaohong Liu, Tao Tan. "**MoEdit: On Learning Quantity Perception for Multi-object Image Editing**", CVPR 2025
- [28] JingYi Yang#, **Zitong Yu#**, Nixiuming, He Jia, Hui Li*. "**Kronecker Mask and Interpretive Prompts are Language-Action Video Learners**", ICLR 2025
- [27] Yawen Cui, Li Liu*, **Zitong Yu***, Guanjie Huang, and Xiaopeng Hong. "**Few-Shot Audio-Visual Class-Incremental Learning with Temporal Prompting and Regularization**", AAAI 2025
- [26] Xilin He, Haijian Liang, Haijian Liang, Boyi Peng, Weicheng Xie, Muhammad Haris Khan, Siyang Song, and **Zitong Yu**. "**MSAmba: Exploring Multimodal Sentiment Analysis with State Space Models**", AAAI 2025
- [25] Xiaole Xian, Xilin He, Zenghao Niu, Junliang Zhang, Weicheng Xie, Siyang Song, **Zitong Yu**, and Linlin Shen. "**CA-Edit: Causality-Aware Condition Adapter for High-Fidelity Local Facial Attribute Editing**", AAAI 2025
- [24] Xun Lin, Yi Yu, **Zitong Yu***, Ruohan Meng, Jiale Zhou, Ajian Liu, Yizhong Liu, Shuai Wang, Wenzhong Tang, Zhen Lei, Alex Kot. "**HideMIA: Hidden Wavelet Mining for Privacy-Enhancing Medical Image Analysis**", ACM MM 2024
- [23] Qilang Ye, **Zitong Yu***, Rui Shao, Xinyu Xie, Philip Torr, Xiaochun Cao. "**CAT: Enhancing Multimodal Large Language Model to Answer Questions in Dynamic Audio-Visual Scenarios**", ECCV 2024
- [22] Kaishen Yuan#, **Zitong Yu#***, Xin Liu*, Weicheng Xie, Huanjing Yue, Jingyu Yang. "**AUFormer: Vision Transformers are Parameter-Efficient Facial Action Unit Detectors**", ECCV 2024
- [21] Xinxu Ge, Xin Liu*, **Zitong Yu***, Jingang Shi, Chun Qi, Jie Li, Heikki Kälviäinen. "**DiffFAS: Face Anti-Spoofing via Generative Diffusion Models**", ECCV 2024
- [20] Qingzheng Huang, Xilin He, Xiaole Xian, Qinliang Lin, Weicheng Xie, Siyang Song, Linlin Shen, **Zitong Yu**. "**MTaDCS: Moving Trace and Feature Density-based Confidence Sample Selection under Label Noise**", ECCV 2024
- [19] Xun Lin, Shuai Wang, Rizhao Cai, Yizhong Liu, Ying Fu, **Zitong Yu***, Wenzhong Tang, Alex Kot. "**Suppress and Balance: Towards Generalized Multi-Modal Face Anti-Spoofing**", CVPR 2024 (Highlight)
- [18] Rizhao Cai, Yawen Cui, Zhi Li, **Zitong Yu***, Haoliang Li, Yongjian Hu, Alex Kot. "**Rehearsal-Free Domain Continual Face Anti-Spoofing: Generalize More and Forget Less**", ICCV 2023 (Oral)
- [17] Xiaobao Guo, Nithish Muthuchamy Selvaraj, **Zitong Yu***, Wai-Kin Adams Kong, Bingquan Shen, Alex Kot. "**Audio-Visual Deception Detection: DOLOS Dataset and Parameter-Efficient Crossmodal Learning**", ICCV 2023
- [16] Hao Lu, **Zitong Yu**, Xuesong Niu, Ying-Cong Chen. "**Neuron Structure Modeling for Generalized Remote Physiological Measurement**", CVPR 2023
- [15] Jianwei Li#, **Zitong Yu#**, Jingang Shi. "**Learning Motion-Robust Remote Photoplethysmography through Arbitrary Resolution Videos**", AAAI 2023
- [14] Jingang Shi, Yusi Wang, Songlin Dong,Changxin Wang, Xiaopeng Hong, **Zitong Yu***, Fei Wang, Yihong Gong. "**IDPT: Interconnected Dual Pyramid Transformer for Face Super-Resolution**", IJCAI 2022
- [13] **Zitong Yu**, Yuming Shen, Jingang Shi, Hengshuang Zhao, Philip Torr, Guoying Zhao. "**PhysFormer: Facial Video-based Physiological Measurement with Temporal Difference Transformer**", CVPR 2022
- [12] Zhuo Wang, Zezheng Wang, **Zitong Yu**, Weihong Deng, Jiahong Li, Tingting Gao, Zhongyuan Wang. "**Domain Generalization via Shuffled Style Assembly for Face Anti-Spoofing**", CVPR 2022
- [11] Haoyu Chen, Hao Tang, **Zitong Yu**, Nicu Sebe, Guoying Zhao. "**Geometry-Contrastive Transformer for Generalized 3D Pose Transfer**", AAAI 2022
- [10] Zhuo Su, Wenzhe Liu, **Zitong Yu**, Dewen Hu, Qing Liao, Qi Tian, Matti Pietikäinen, and Li Liu. "**Pixel Difference Networks for Efficient Edge Detection**", ICCV 2021 (Oral)
- [9] **Zitong Yu**, Yunxiao Qin, Hengshuang Zhao, Xiaobai Li, and Guoying Zhao. "**Dual-Cross Central Difference Network for Face Anti-Spoofing**." IJCAI 2021
- [8] Ruijing Yang, Ziyu Guan, **Zitong Yu**, Guoying Zhao, Xiaoyi Feng and Jinye Peng. "**Non-contact Pain Recognition from Video Sequences with Remote Physiological Measurements Prediction**." IJCAI 2021
- [7] Xin Liu, Henglin Shi, Haoyu Chen, **Zitong Yu**, Xiaobai Li, and Guoying Zhao. "**iMiGUE: An Identity-free Video Dataset for Micro-Gesture Understanding and Emotion Analysis**." CVPR 2021
- [6] **Zitong Yu**, Xiaobai Li, Xuesong Niu, Jingang Shi, and Guoying Zhao. "**Face anti-spoofing with human material perception**." ECCV 2020
- [5] Xuesong Niu, **Zitong Yu**, Hu Han, Xiaobai Li, Shiguang Shan, and Guoying Zhao. "**Video-based Remote Physiological Measurement via Cross-verified Feature Disentangling**." ECCV 2020 (Oral)
- [4] **Zitong Yu**, Chenxu Zhao, Zezheng Wang, Yunxiao Qin, Zhuo Su, Xiaobai Li, Feng Zhou, and Guoying Zhao. "**Searching central difference convolutional networks for face anti-spoofing**." CVPR 2020
- [3] Zezheng Wang, **Zitong Yu**, Chenxu Zhao, Xiangyu Zhu, Yunxiao Qin, Qiusheng Zhou, Feng Zhou, and Zhen Lei. "**Deep spatial gradient and temporal depth learning for face anti-spoofing**." CVPR 2020 (Oral)
- [2] Yunxiao Qin, Chenxu Zhao, Xiangyu Zhu, Zezheng Wang, **Zitong Yu**, Tianyu Fu, Feng Zhou, Jingping Shi, and Zhen Lei. "**Learning meta model for zero-and few-shot face anti-spoofing**." AAAI 2020 (Spotlight)
- [1] **Zitong Yu#**, Wei Peng#, Xiaobai Li, Xiaopeng Hong, and Guoying Zhao. "**Remote heart rate measurement from highly compressed facial videos: an end-to-end deep learning solution with video enhancement**." ICCV 2019

# Research Grants
- General Program of the Natural Science Foundation of China (PI), 500k RMB, 2026-01 to 2029-12.
- CCF-Tencent Rhino Bird Grant 2025 CCF-腾讯犀牛鸟 (PI), 150k RMB, 2025-10 to 2026-09.
- Excellent Young Scholars (Overseas) Fund of the Natural Science Foundation of China 国家优青(海外) (PI), 1000k RMB, 2025-01 to 2027-12.
- Young Scientists Fund of the Natural Science Foundation of China (PI), 300k RMB, Grant No. 62306061, 2024-01 to 2026-12.
- Guangdong Provincial Regional Joint Fund - Regional Cultivation Project (PI), 300k RMB, Grant No. 2023A1515140037, 2024-01 to 2026-12.
- Open Project of National Engineering Laboratory for Big Data System Computing Technology, Shenzhen University, (PI), 50k RMB, Grant No. SZU-BDSC-OF2024-02, 2024-01 to 2025-12.
- Open Project of Guangdong Provincial Key Laboratory of Intelligent Information Processing, Shenzhen University (PI), 80k RMB, Grant No. 2023B1212060076, 2025-01 to 2026-12.
- Open Project of MoE Key Laboratory of Information Technology, Sun Yat-sen University (PI), 20k RMB, 2025-01 to 2025-12.

# Honors & Awards
- Recipient of 2025 广东省计算机学会优秀论文奖一等奖
- Recipient of 第十五届粤港澳图象图形学术会议优秀论文奖一等奖
- Recipient of Dongguan Innovation Youth Science and Technology Award （创新东莞青年科技奖）
- Recipient of 2025 ACM SIGWEB China 新星奖
- Awarded as 2025 GDSIG Science and Technology Progress First Prize (广东省图象图形学会科技进步一等奖，序1)
- 2nd Place on REACT2025 Third Multiple Appropriate Facial Reaction Generation Challenge @ACM MM 25 Offline Generation Track
- FusionMamba is selected as the first Cover Article (首个封面文章) of the Visual Intelligence journal
- Recipient of 隐者联盟 2024 年度优秀论文奖
- Recipient of 2024 深圳市优秀科技学术论文奖
- Recipient of Best Paper Honorable Mention Award (最佳论文提名) of CCBR 2024
- Recipient of Best Paper Candidate (最佳论文提名) of ICME 2024
- Recipient of IAPR Best Student Paper Award of CCBR'23 (IAPR最佳学生论文奖)
- Recipient of World's Top 2% Scientists 2023-2025 (连续三年入选（2023-2025）斯坦福全球前2%顶尖科学家榜单)
- Recipient of the second prize of the IEEE Finland Jt. Chapter SP/CAS Best Paper Award (2022)
- Recipient of Chinese Government Award 2021 for Outstanding Self-financed Students Abroad (国家优秀自费留学生奖)
- Recipient of IEEE Finland Section best student conference paper award 2020
- 1st Place in the ChaLearn multi-modal face anti-spoofing attack detection challenge @ CVPR 2020
- 2nd Place on Action Recognition Track of ECCV 2020 VIPriors Challenges
- Master Program Scholarship of Pays de la Loire, France
 
<span class='anchor' id='experience'></span>
# Membership
- CCF东莞分部秘书长 (2024-2026)
- CSIG生物特征识别专业委员会（筹）副秘书长
- 东莞市智能信息技术重点实验室副主任
- IEEE/CCF/CSIG Senior Member, CAAI/CAA Member
- CCF多媒体专业委员会执行委员，CAA模式识别与机器智能专业委员会委员
- CSIG青年工作委员会委员，CSIG数字媒体取证与安全专委会委员

# Organizing scientific activities
- [2nd Workshop & Challenge on Subtle Visual Computing (SVC)](https://sites.google.com/view/svc-cvpr26) @ CVPR 2026
- [Publicity Chair of IAPR/IEEE Winter School on Biometrics 2025](https://www.comp.hkbu.edu.hk/wsb2026/committee.php)
- [CCBR 2025 论坛主席](https://ccbr99.cn/organizers.html)
- [1st Workshop & Challenge on Subtle Visual Computing (SVC)](https://sites.google.com/view/svc-mm25) @ ACM MM 2025
- Co-organizing 3D High-Fidelity Mask Face Presentation Attack Detection Challenge ICCV2021
- Co-organizing the first Challenge on Remote Physiological Signal Sensing (RePSS) with CVPR 2020

# Invited talks
- 'Subtle Visual Computing', GSIS 12th International Research Seminar @ University of Hyogo, 23.04.2025
- '人脸反欺诈技术的一些思考', CSIG青年学者学术交流会《复杂应用场景下的人脸安全与取证技术》, 20.01.2025
- KEYNOTE 'Facial Physiological and Emotional Analysis', ACM MM2024 - Multimodal and Responsible Affective Computing (MRAC 2023), 01.11.2024
- '多模态大模型幻觉与鲁棒的一些思考', CCBR 2024 - 生物特征安全论坛, 24.11.2024
- '垂类视觉基础模型的一些思考', Visual Intelligence“视觉基础模型”专刊交流会, 21.07.2024
- '可信人脸生理感知与安全', SAILING讲坛第十四期，广东省安全智能新技术重点实验室, 24.06.2024
- '迈向可信赖的人脸生理感知和安全系统', 第三届多媒体智能安全学术研讨会 (隐者联盟∙洪都论道 MAS'2024), 14.04.2024
- KEYNOTE 'Towards Trustworthy Face Physiological Sensing and Security Systems', WACV2023 - Workshop on Manipulation, Adversarial, and Presentation Attacks in Biometrics, 07.01.2023
- 'Towards Trustworthy Face Physiological Sensing and Security Systems', Valse Webinar, 14.12.2022
- 'Non-Contact Human Sensing and Biometric Security’, Hong Kong Baptist University, 02.11.2021
- 'Non-Contact Human Sensing and Biometric Security’, Southern University of Science and Technology, 08.11.2021
- 'Face Anti-Spoofing Attack Detection Techniques’, University of Jyväskylä, 28.03.2022

<span class='anchor' id='services'></span>
# Invited Journal Reviewer
- IEEE Transactions on Pattern Analysis and Machine Intelligence (since 2021)
- International Journal of Computer Vision (since 2022)
- IEEE Transactions on Image Processing (since 2020)
- IEEE Transactions on Neural Networks and Learning Systems (since 2021)
- IEEE Transactions on Information Forensics and Security (since 2021)
- IEEE Transactions on Dependable and Secure Computing (since 2021)
- IEEE Transactions on Circuits and Systems for Video Technology (since 2020)
- IEEE Transactions on Biometrics, Behavior, and Identity Science (since 2020)
- Pattern Recognition & Pattern Recognition Letters (since 2020)
- IEEE Journal of Biomedical and Health Informatics (since 2020)
- IET Biometrics (since 2022)
- Security and Communication Networks (since 2021)
- Journal of Visual Communication and Image Representation (since 2021)
- ACM Transactions on Multimedia Computing, Communications and Applications (TOMM) (since 2021)

# Associate Editor (AE) or Consulting Area Editor (CAE)
- [Machine Intelligence Research](https://www.mi-research.net/) (MIR, JCR Q1) 青年编委
- [CAE of IEEE Transactions on Information Forensics and Security](https://signalprocessingsociety.org/publications-resources/ieee-transactions-information-forensics-and-security/editorial-board) (CCF-A)
- [Frontiers in Artificial Intelligence](https://loop.frontiersin.org/people/2376790/overview) (IF=4.0)
- [《网络空间安全科学学报》](https://www.journalofcybersec.com/CN/home) 青年编委

# Guest Editors
- Special Issue "Subtle Visual Computing" on Machine Intelligence Research (IF=6.4)
- Special Issue "Deep Learning Approach for Secure and Trustworthy Biometric System" on MDPI Electronics (IF=2.69)
- Special Issue "Trustworthy Multimodal Biometrics Authentication" on IET Biometrics (IF=1.8)

# Invited Conference Area Chair
- ICME'23, BMVC'24, IJCB'24, AAAI'25 (SPC), ACM MM'25, BMVC'25, IJCAI-ECAI'26 (SPC)

# Invited Conference Reviewer
- CVPR'25, ICCV'25, ICLR'26, CVPR'26
- AAAI'24, ICLR'24, CVPR'24, IJCAI'24, ECCV'24, PRCV'24, NeurIPS'24
- AAAI'23, CVPR'23, IJCAI'23, ICCV'23, IJCB'23, NeurIPS'23, SIGGRAPH Asia'23, PRCV'23
- AAAI'22, CVPR'22, ICME'22, IJCAI'22, ECCV'22, PRCV'22,
- ICME'21, ICCV'21

<span class='anchor' id='teaching'></span>
# Teaching
- lecturer for Introduction to Computer Science (CS101), Great Bay Univesity, Autumn 2025
- Teaching assistant (TA) for Computer Graphics (521140S), University of Oulu, Spring 2020, 2021
