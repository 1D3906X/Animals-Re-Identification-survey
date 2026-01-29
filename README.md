<div align="center">
  <h2><i>Animals-Re-Identification-survey</i></h2> 
</div>

<div align="center">
Collect various papers about re-identification for animals towards better generalization
</div>

# Content
- [Papers](#papers)
  - [Problems and Challenges](#problems-and-challenges)
    - [Long-Tailed Distribution](#long-tailed-distribution)
    - [Real-World Ecological Challenges](#real-world-ecological-challenges)
  - [Cross-Species Transfer Learning](#cross-species-transfer-learning)
    - [Pretrained Model Transfer](#pretrained-model-transfer)
    - [Cross-Domain Transfer](#cross-domain-transfer)
    - [Taxonomy-Driven Transfer](#taxonomy-driven-transfer)
  - [Few-Shot Learning](#few-shot-learning)
    - [Few-Shot Classification](#few-shot-classification)
    - [Few-Shot Object Detection](#few-shot-object-detection)
    - [Few-Shot Applications in Ecology](#few-shot-applications-in-ecology)
  - [Domain Generalization](#domain-generalization)
    -  [Cross-Environment Generalization](#cross-environment-generalization)
    -  [Out-of-Distribution Generalization](#out-of-distribution-generalization)
    -  [Multimodal Generalization](#multimodal-generalization)
  -  [Applications Systems and Benchmarks](#applications-systems-and-benchmarks)
    -  [Camera Trap](#camera-trap)
    -  [Ecological Monitoring Systems](#ecological-monitoring-systems)
- [Supplemental Tools](#supplemental-tools)

# Papers

## Problems and Challenges

### Long-Tailed Distribution
- **Deep Long-Tailed Learning: A Survey**.  *Yifan Zhang, Bingyi Kang, Bryan Hooi, Shuicheng Yan, Fellow, IEEE, and Jiashi Feng*.  [[DOI](https://arxiv.org/abs/2110.04596)][[pdf](https://arxiv.org/pdf/2110.04596)][[code](https://github.com/Vanint/Awesome-LongTailed-Learning)] ![](https://img.shields.io/badge/arXiv2021-red)
- **A Survey on Long-Tailed Visual Recognition**.  *Lu Yang, He Jiang, Qing Song, Jun Guo*.  [[DOI](https://arxiv.org/abs/2205.13775)] [[pdf](https://arxiv.org/pdf/2205.13775)] ![](https://img.shields.io/badge/arXiv2022-red)
- **Bag of Tricks for Long-Tail Visual Recognition of Animal Species in Camera-Trap Images**.  *Fagner Cunha, Eulanda M. dos Santos, Juan G. Colonna*.  [[DOI](https://arxiv.org/abs/2206.12458)] [[pdf](https://arxiv.org/pdf/2206.12458)] ![](https://img.shields.io/badge/arXiv2022-red)
- **Long-Tailed Metrics and Object Detection in Camera Trap Datasets**.  *Wentong He, Ze Luo, Xinyu Tong, Xiaoyi Hu, Can Chen and Zufei Shu*.  [[DOI](https://www.mdpi.com/2076-3417/13/10/6029)] ![](https://img.shields.io/badge/MDPI2023-purple)
- **Overcoming Classifier Imbalance for Long-tail Object Detection with Balanced Group Softmax**.  *Yu Li, Tao Wang, Bingyi Kang, Sheng Tang, Chunfeng Wang, Jintao Li, Jiashi Feng*.  [[DOI](https://arxiv.org/abs/2006.10408)] [[pdf](https://arxiv.org/pdf/2006.10408)] [[code](https://github.com/FishYuLi/BalancedGroupSoftmax)] ![](https://img.shields.io/badge/arXiv2020-red)
- **Long-tailed visual recognition with deep models: A methodological survey and evaluation**.  *Yu Fu, Liuyu Xiang, Yumna Zahid, Guiguang Ding, Tao Mei, Qiang Shen, Jungong Han*.  [[DOI](https://www.sciencedirect.com/science/article/abs/pii/S0925231222010062)] ![](https://img.shields.io/badge/ScienceDirect2022-orange)
- **Equalization Loss for Long-Tailed Object Recognition**.  *Jingru Tan, Changbao Wang, Buyu Li, Quanquan Li, Wanli Ouyang, Changqing Yin, Junjie Yan*.  [[DOI](https://arxiv.org/abs/2003.05176)] [[pdf](https://arxiv.org/pdf/2003.05176)] [[code](https://github.com/tztztztztz/eql.detectron2)] ![](https://img.shields.io/badge/arXiv2020-red)
- **FASA: Feature Augmentation and Sampling Adaptation for Long-Tailed Instance Segmentation**.  *Yuhang Zang, Chen Huang, Chen Change Loy*.  [[DOI](https://arxiv.org/abs/2102.12867)] [[pdf](https://arxiv.org/pdf/2102.12867)] [[code](https://github.com/yuhangzang/FASA)] ![](https://img.shields.io/badge/arXiv2021-red)

### Real-World Ecological Challenges
- **Automatically identifying, counting, and describing wild animals in camera-trap images with deep learning**.  *Mohammad Sadegh Norouzzadeh, Anh Nguyen, Margaret Kosmala, Alexandra Swanson, Meredith S Palmer, Craig Packer, Jeff Clune*.  [[DOI](https://pubmed.ncbi.nlm.nih.gov/29871948/)] ![](https://img.shields.io/badge/OSTI2018-blue)
- **Insights and approaches using deep learning to classify wildlife**.  *Zhongqi Miao, Kaitlyn M. Gaynor, Jiayun Wang, Ziwei Liu, Oliver Muellerklein, Mohammad Sadegh Norouzzadeh, Alex McInturff, Rauri C. K. Bowie, Ran Nathan, Stella X. Yu & Wayne M. Getz*.  [[DOI](https://www.nature.com/articles/s41598-019-44565-w)] ![](https://img.shields.io/badge/Nature2019-blue)


## Cross-Species Transfer Learning

### Pretrained Model Transfer
- **Transfer learning on animal species recognition tasks**.  *Haotian Zhu*.  [[DOI](https://aei.ewapub.com/article/view/15888)] [[pdf](https://aei.ewapub.com/article/view/15888.pdf)] ![](https://img.shields.io/badge/AEI2024-blue)
- **Animal Image Classification Using DenseNet-161 Transfer Learning: A Comprehensive Deep Learning Approach for Multi-Species Recognition**.  *Devanshi Shah*.  [[DOI](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5990514)] ![](https://img.shields.io/badge/SSRN2026-blue)
- **Bird species recognition using transfer learning with a hybrid hyperparameter optimization scheme (HHOS)**.  *Samparthi V.S. Kumar
, Hari Kishan Kondaveeti*.  [[DOI](https://www.sciencedirect.com/science/article/pii/S1574954124000529)] [[pdf](https://pdf.sciencedirectassets.com/273474/1-s2.0-S1574954123X00077/1-s2.0-S1574954124000529/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQDHXDEh%2B7cYPlFhYyexyNI1%2Bbt%2B92r476j7IoSTrmMzqAIgJRCLQHaJjdFhKouxPG6QcDkLm422Hh8ECK9yVkx1HcEqswUIZRAFGgwwNTkwMDM1NDY4NjUiDLaXkB5BO7pvfZW5nyqQBcE2brkdAQWnjYE1Z4vcP6tF96turOKEyvcUntt8or6J%2Fo4BW2g67V9%2F3FTAeZ29HOZtnrn7EiUYy7nX9Ep3d13bHXcYhcATS1%2BWw1cXHufACMQX0wanDPTE8uA8ETXy8NVe9TPREp8qdjn0sYQKRabTro1JWPtooHM8OG4U6kj0d7M4VQ1F6sx%2BbTm0tytV0omProXmAuo4iXiURt00vcPyZY0gCuBNGt%2BlzmB6TP9%2Fs4whVjob31%2FWZC8RMokuLsZQicjUdeCdQQ4UfbbPXb1Js%2B7F03haTvZNwrCWPsTpquZdE0SEoYxg7pi1eTmWSx%2FNtYN9lsOI2p99q2BLRU%2FACuuT72o1cbf0%2BmryJj1D%2Fo72GUNc%2BDiuejWLDxLRnw18ygVeo%2F2EGVZfIBTSb0ORwv%2BnOZSFddr6cgTQUS9%2FeueJuE3HLFWZznmEB0m9odIRWfHB0mK8hGPtDqEfH6zhTOMcYRiFjhF7kgUMUXDWYXJPmqVIXhpdn1B%2BNGRTQ2RZ6PIgUhqXm5CFsjkl5iqvhxjRHESPFNkjZ31T24c6iXv3US2yDGNR3aVbeB5JbZYSPjPId%2BEADU2IKTkOG8ZWIIwSeCY6s1xPKmz6d4fd22qLZOkvB1INhivGnpUvAHD1pVUqLqCa0A7yuyCWcHKbjjekia%2FtBY2qMztv1cRq6p%2FhDE%2BWk6pAi%2FhClQlWAKzL0I%2BvhMabNwOAA7%2BJojdMFWOFN0xc0PuV4vrk1k0%2FD1pgstbVGaj69yIY5N1rZKvEJqS%2B7mDl5%2Fgf6I3eWOChjLHKPTyaVBKHkaVeQhWlxvuI9Wmg0vlx4qIOrPYmZ7nRKiFaTsKKmuJ1nYsLALgur4T1gZKvTdmhTmZl4W1gMNKU5ssGOrEBIZhZc4UDEY1VsuXGlgjtopLk441BRdKKO3cBbDZPmPqkNm0HWROcDpkWSxl9EuzPqVOG5zbhlltQKb4tkXQWK6RJbvNiIrzIDI7VWeYVlJA66kwpSmldXp8xBFrvjqSNruae83z2Gf%2FxgaHzFwjk%2BTaA6jvNOt6%2F2smSB1b3Kzo2v04MZSQj2rgXhwVoQsB3bfYH7KBbfwQFMl8PhloCi60MbHNko2N%2FoNS7dVUtbyu7&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20260128T043757Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYU3V5SUSD%2F20260128%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=e22a082a705e9a561f3af08f6576036c9a6c04b16f4ac1d0e9e7ec04bdf3a616&hash=7b70d6b591f371ed3639d95fa656016984f24886380c62873ef00013d9f38605&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1574954124000529&tid=spdf-e43fc0b1-c4d4-4d09-ba75-b8f9b173ab8f&sid=c0480a073d22b7435f585a588abcbb1aceb3gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=0f1c5c02560b010d5353&rr=9c4dcc26ae117c24&cc=us&kca=eyJrZXkiOiJhdVFqMmw1azg5M3gyNUtRa21nTVhQeHA3QjZSVzNPVE5Wb1FobTIwQlB1bWFEc203a0hMTzdoSVdMOEtGS2VmSmN5TUNnS1crUDNhWS96aEIyMGdEeEZxMGRNSUxNRkxqZ1VwbFBrd25XWUV0aDkxR2x3enJYTHJEU2RydnNRbFRjc3FBMWlYWUpLVXUwQ1ZNUUphN3FXaVBwVHUxQUN0QklXY3M3Qkg3N2xGODBnZ3BRPT0iLCJpdiI6IjFkNTM0Yzk4ZTVlYWRiMmQ1NTBjMjQ5ODhiYzMwM2IyIn0=_1769575091623)] ![](https://img.shields.io/badge/ScienceDirect2024-orange)
- **Automatically identifying, counting, and describing wild animals in camera-trap images with deep learning**.  *Mohammad Sadegh Norouzzadeh, Anh Nguyen, Margaret Kosmala, Alexandra Swanson, Meredith S Palmer, Craig Packer, Jeff Clune*.  [[DOI](https://pmc.ncbi.nlm.nih.gov/articles/PMC6016780/)] [[pdf](https://pmc.ncbi.nlm.nih.gov/articles/PMC6016780/pdf/pnas.201719367.pdf)] [[code](https://github.com/Evolving-AI-Lab/deep_learning_for_camera_trap_images)] ![](https://img.shields.io/badge/NIH2018-blue)
- **TransMatch: A Transfer-Learning Scheme for Semi-Supervised Few-Shot Learning**.  *Zhongjie Yu, Lin Chen, Zhongwei Cheng, Jiebo Luo*.  [[DOI](https://arxiv.org/abs/1912.09033)] [[pdf](https://arxiv.org/pdf/1912.09033)] ![](https://img.shields.io/badge/arXiv2020-red)

### Cross-Domain Transfer
- **UniAP: Towards Universal Animal Perception in Vision via Few-shot Learning**.  *Meiqi Sun, Zhonghan Zhao, Wenhao Chai, Hanjun Luo, Shidong Cao, Yanting Zhang, Jenq-Neng Hwang, Gaoang Wang*.  [[DOI](https://arxiv.org/abs/2308.09953)] [[pdf](https://arxiv.org/pdf/2308.09953)] ![](https://img.shields.io/badge/arXiv2023-red)
- **Applying Few-Shot Learning for In-the-Wild Camera-Trap Species Classification**.  *Haoyu Chen,Stacy Lindshield,Papa Ibnou Ndiaye,Yaya Hamady Ndiaye,Jill D. Pruetz and Amy R. Reibman*.  [[DOI](https://www.mdpi.com/2673-2688/4/3/31)] [[code](https://github.com/microsoft/SpeciesClassification)] ![](https://img.shields.io/badge/MDPI2023-green)
- **Cross-Domain Few-Shot Classification via Learned Feature-Wise Transformation**.  *Hung-Yu Tseng, Hsin-Ying Lee, Jia-Bin Huang, Ming-Hsuan Yang*.  [[DOI](https://arxiv.org/abs/2001.08735)] [[pdf](https://arxiv.org/pdf/2001.08735)] [[code](https://github.com/hytseng0509/CrossDomainFewShot)] ![](https://img.shields.io/badge/arXiv2020-red)
- **Deep Learning for Cross-Domain Few-Shot Visual Recognition: A Survey**.  *Huali Xu, Shuaifeng Zhi, Shuzhou Sun, Vishal M. Patel, Li Liu*.  [[DOI](https://dl.acm.org/doi/full/10.1145/3718362)] [[pdf](https://dl.acm.org/doi/epdf/10.1145/3718362)] ![](https://img.shields.io/badge/ACM2025-black)
- **Zero-Shot Learning -- A Comprehensive Evaluation of the Good, the Bad and the Ugly**.  *Yongqin Xian, Christoph H. Lampert, Bernt Schiele, Zeynep Akata*.  [[DOI](https://arxiv.org/abs/1707.00600)] [[pdf](https://arxiv.org/pdf/1707.00600)] ![](https://img.shields.io/badge/arXiv2020-red)
- **Zero-Shot Learning -- The Good, the Bad and the Ugly**. *Yongqin Xian, Bernt Schiele, Zeynep Akata* [[DOI](https://ieeexplore.ieee.org/document/8099811)] [[pdf](https://openaccess.thecvf.com/content_cvpr_2017/papers/Xian_Zero-Shot_Learning_-_CVPR_2017_paper.pdf)] ![](https://img.shields.io/badge/CVPR2017-blue)
- **Adaptive Confidence Smoothing for Generalized Zero-Shot Learning**.  *Yuval Atzmon, Gal Chechik*.  [[DOI](https://ieeexplore.ieee.org/document/8953714)] [[pdf](https://openaccess.thecvf.com/content_CVPR_2019/papers/Atzmon_Adaptive_Confidence_Smoothing_for_Generalized_Zero-Shot_Learning_CVPR_2019_paper.pdf)] [[code]()] ![](https://img.shields.io/badge/CVPR2019-blue)

### Taxonomy-Driven Transfer
- **CLIP-Driven Few-Shot Species-Recognition Method for Integrating Geographic Information**.  *Lei Liu,Linzhe Yang,Feng Yang,Feixiang Chen and Fu Xu*.  [[DOI](https://www.mdpi.com/2072-4292/16/12/2238)] ![](https://img.shields.io/badge/MDPI2024-green)
- **UniAP: Towards Universal Animal Perception in Vision via Few-shot Learning**.  *Meiqi Sun, Zhonghan Zhao, Wenhao Chai, Hanjun Luo, Shidong Cao, Yanting Zhang, Jenq-Neng Hwang, Gaoang Wang*.  [[DOI](https://arxiv.org/abs/2308.09953)] [[pdf](https://arxiv.org/pdf/2308.09953)] ![](https://img.shields.io/badge/arXiv2023-red)
- **AP-10K: A Benchmark for Animal Pose Estimation in the Wild**.  *Hang Yu, Yufei Xu, Jing Zhang, Wei Zhao, Ziyu Guan, Dacheng Tao*.  [[DOI](https://arxiv.org/abs/2108.12617)] [[pdf](https://datasets-benchmarks-proceedings.neurips.cc/paper_files/paper/2021/file/903ce9225fca3e988c2af215d4e544d3-Paper-round2.pdf)] [[code](https://github.com/AlexTheBad/AP-10K)] ![](https://img.shields.io/badge/NeurIPS2021-black)
- **Utilizing Geographical Distribution Statistical Data to Improve Zero-Shot Species Recognition**.  *Lei Liu,Boxun Han,Feixiang Chen, Chao Mou and Fu Xu*.  [[DOI](https://www.mdpi.com/2076-2615/14/12/1716)] ![](https://img.shields.io/badge/MDPI2024-green)
- **Review on Animal Species Recognition using Transfer Learning VGG16 Model)**.  *Mayuri M. Vengurlekar, Ashish Pal, Pravin Parihar, Mustafa Nandervawala, Saahil Parmar, Shankar Amalraj*. [[pdf](https://kitspress.com/journals/IJDSAI/content/02/06/IJDSAI_V02_06_170-175-03112024.pdf)] [[code]()] ![](https://img.shields.io/badge/IJDSAI2024-blue)


## Few-Shot Learning

### Few-Shot Classification
- **Few-Shot Object Detection: Research Advances and Challenges**.  *Zhimeng Xin, Shiming Chen, Tianxu Wu, Yuanjie Shao, Weiping Ding, Xinge You*.  [[DOI](https://arxiv.org/abs/2404.04799)] [[pdf](https://arxiv.org/pdf/2404.04799)] ![](https://img.shields.io/badge/arXiv2024-red)
- **Few-Shot Object Detection: A Comprehensive Survey**.  *Mona Köhler, Markus Eisenbach, Horst-Michael Gross*.  [[DOI](https://ieeexplore.ieee.org/abstract/document/10103630)] [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10103630)]  ![](https://img.shields.io/badge/CVPR2024-blue)
- **Universal-Prototype Enhancing for Few-Shot Object Detection**.  *Aming Wu, Yahong Han, Linchao Zhu, Yi Yang*.  [[DOI](https://arxiv.org/abs/2103.01077)] [[pdf](https://arxiv.org/pdf/2103.01077)] [[code](https://github.com/AmingWu/UP-FSOD)] ![](https://img.shields.io/badge/ICCV2021-blue)
- **Few-shot Object Detection via Improved Classification Features**.  *Xinyu Jiang, Zhengjia Li, Maoqing Tian, Jianbo Liu, Shuai Yi, Duoqian Miao*. [[pdf](https://iip.tongji.edu.cn/pdf/2023WACV-jyx.pdf)] ![](https://img.shields.io/badge/WACV2023-black)
- **Label, Verify, Correct: A Simple Few Shot Object Detection Method**.  *Prannay Kaul, Weidi Xie, Andrew Zisserman*.  [[DOI](https://arxiv.org/abs/2112.05749)] [[pdf](https://arxiv.org/pdf/2112.05749)] ![](https://img.shields.io/badge/CVPR2022-orange)

### Few-Shot Object Detection

### Few-Shot Applications in Ecology



## Domain Generalization

### Cross-Environment Generalization

### Out-of-Distribution Generalization

### Multimodal Generalization


## Applications Systems and Benchmarks

### Camera Trap

### Ecological Monitoring Systems


# Supplemental Tools
- **CameraTrapDetectoR**. [[code](https://github.com/CameraTrapDetectoR)]*检测、分类、计数相机陷阱图像中的动物,无代码操作,大规模批处理*.
- **MegaDetector**.[[code](https://github.com/agentmorris/MegaDetector)]*微软社区的主流相机陷阱 AI 模型,很多生态、保护区、政府项目用它来过滤空图像（blank）和标记动物/人/车,它训练于来自全球不同栖息地的大量数据,是当前生态监测中最实用、引用最广的基础工具，被大量论文使用*.
- **AddaxAI**.[[web](https://addaxdatascience.com/addaxai/)]*面向生态专家/研究者的本地运行平台，集成了 MegaDetector，可视化图像分析、标签导出、GPU 加速,支持 human-in-the-loop 校验结果*.
- **Google CameraTrapAI**[[code](https://github.com/google/cameratrapai)]*由 Google 开源的 SpeciesNet + MegaDetector 大规模物种识别组合模型，可用于对图像中的动物进行species级识别,并支持高层次分类（哺乳类、猫科、车辆等）,对生态研究极具价值，可用于大规模长期监测和稀有物种检测实验*.
- **TrapTagger**.[[code](https://github.com/WildEyeConservation/TrapTagger)]*来自 Oxford WildCRU、用于管理、注释、组织大量相机陷阱图像的系统，支持自动分析,混合注释,自己训练 species classifier,大规模多年份生态监测数据处理,物种分类,数据库式管理, Web / AWS 可部署系统*.
- **Animal Detect**.[[web](https://www.animaldetect.com/)]*网页式 workflow 工具，用于上传图像、筛空、分类、导出标注和生成可视化汇总，支持拖拽上传、自动批处理、导出 COCO 格式标注,内置 species 分类,在全球众多保护组织和研究团队中有真实使用案例*
