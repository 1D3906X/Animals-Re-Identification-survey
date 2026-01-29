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
    - [Cross-Environment Generalization](#cross-environment-generalization)
    - [Out-of-Distribution Generalization](#out-of-distribution-generalization)
    - [Multimodal Generalization](#multimodal-generalization)
  - [Applications Systems and Benchmarks](#applications-systems-and-benchmarks)
    - [Camera Trap](#camera-trap)
    - [Ecological Monitoring Systems](#ecological-monitoring-systems)
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
, Hari Kishan Kondaveeti*.  [[DOI](https://www.sciencedirect.com/science/article/pii/S1574954124000529)] ![](https://img.shields.io/badge/ScienceDirect2024-orange)
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
- **Few-Shot Object Detection via Variational Feature Aggregation**. *Jiaming Han, Yuqiang Ren, Jian Ding, Ke Yan, Gui-Song Xia*. [[DOI](https://ojs.aaai.org/index.php/AAAI/article/view/25153)] [[pdf](https://arxiv.org/pdf/2301.13411)] [[code](https://github.com/csuhan/VFA)] ![](https://img.shields.io/badge/AAAI2023-blue)
- **Hierarchical Few-Shot Object Detection: Problem, Benchmark and Method**.  *Lu Zhang, Yang Wang, Jiaogen Zhou, Chenbo Zhang, Yinglu Zhang, Jihong Guan, Yatao Bian, Shuigeng Zhou*.  [[DOI](https://dl.acm.org/doi/abs/10.1145/3503161.3548412)] [[pdf](https://dl.acm.org/doi/epdf/10.1145/3503161.3548412)] [[code](https://github.com/zhanglu-cst/HIFSOD/tree/main)] ![](https://img.shields.io/badge/ACM2022-black)
- **Few-Shot Object Detection with Foundation Models**.  *Guangxing Han, Ser-Nam Lim*.  [[DOI](https://ieeexplore.ieee.org/document/10658367)] [[pdf](https://openaccess.thecvf.com/content/CVPR2024/papers/Han_Few-Shot_Object_Detection_with_Foundation_Models_CVPR_2024_paper.pdf)] ![](https://img.shields.io/badge/CVPR2024-blue)
- **Few-Shot Object Detection with Sparse Context Transformers**.  *Jie Mei, Mingyuan Jiu, Hichem Sahbi, Xiaoheng Jiang, Mingliang Xu*.  [[DOI](https://arxiv.org/abs/2402.09315)] [[pdf](https://arxiv.org/pdf/2402.09315)] ![](https://img.shields.io/badge/arXiv2024-red)

### Few-Shot Applications in Ecology
- **A Few-Shot Object Detection Method for Endangered Species**.  *Hongmei Yan, Xiaoman Ruan, Daixian Zhu, Haoran Kong and Peixuan Liu*.  [[DOI](https://www.mdpi.com/2076-3417/14/11/4443)] ![](https://img.shields.io/badge/MDPI2024-purple)
- **The Art of Camouflage: Few-Shot Learning for Animal Detection and Segmentation**.  *Thanh-Danh Nguyen, Anh-Khoa Nguyen Vu, Nhat-Duy Nguyen, Vinh-Tiep Nguyen, Thanh Duc Ngo, Thanh-Toan Do*.  [[DOI](https://ieeexplore.ieee.org/abstract/document/10608133)] [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10608133)] [[code](https://github.com/danhntd/FS-CDIS-Few-shot-Camouflaged-Detection-and-Segmentation)] ![](https://img.shields.io/badge/IEEEAccess2024-blue)
- **Multiobject Tracking of Wildlife in Videos Using Few-Shot Learning**.  *Jiangfan Feng and Xinxin Xiao*.  [[DOI](https://www.mdpi.com/2076-2615/12/9/1223)] ![](https://img.shields.io/badge/MDPI2022-purple)
- **Generalization-Enhanced Few-Shot Object Detection in Remote Sensing**.  *Hui Lin, Nan Li, Pengjuan Yao, Kexin Dong, Yuhan Guo, Danfeng Hong*.  [[DOI](https://ieeexplore.ieee.org/abstract/document/10836905)] [[code](https://github.com/leenamx/GE-FSOD)] ![](https://img.shields.io/badge/TCSVT2025-blue)


## Domain Generalization

### Cross-Environment Generalization
- **Recognition in Terra Incognita**.  *Sara Beery, Grant van Horn, Pietro Perona*.  [[DOI](https://arxiv.org/abs/1807.04975)] [[pdf](https://openaccess.thecvf.com/content_ECCV_2018/papers/Beery_Recognition_in_Terra_ECCV_2018_paper.pdf)] [[code](https://beerys.github.io/CaltechCameraTraps/)] ![](https://img.shields.io/badge/ECCV2018-green)
- **The iWildCam 2020 Competition Dataset**.  *Sara Beery, Elijah Cole, Arvi Gjoka*.  [[DOI](https://arxiv.org/abs/2004.10340)] [[pdf](https://arxiv.org/pdf/2004.10340)] ![](https://img.shields.io/badge/CVPR2020-blue)
- **Wilds: A Benchmark of In-the-Wild Distribution Shifts**.  *Pang Wei Koh, Shiori Sagawa, Henrik Marklund, Sang Michael Xie, Marvin Zhang, Akshay Balsubramani, Weihua Hu, Michihiro Yasunaga, Richard Lanas Phillips, Irena Gao, Tony Lee, Etienne David, Ian Stavness, Wei Guo, Berton A. Earnshaw, Imran S. Haque, Sara Beery, Jure Leskovec, Anshul Kundaje, Emma Pierson, Sergey Levine, Chelsea Finn, Percy Liang*.  [[DOI](https://arxiv.org/abs/2012.07421)] [[pdf](https://arxiv.org/pdf/2012.07421)] ![](https://img.shields.io/badge/arXiv2020-red)
- **Do Better ImageNet Models Transfer Better?**.  *Simon Kornblith, Jonathon Shlens, Quoc V. Le*.  [[DOI](https://arxiv.org/abs/1805.08974)] [[pdf](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kornblith_Do_Better_ImageNet_Models_Transfer_Better_CVPR_2019_paper.pdf)] ![](https://img.shields.io/badge/CVPR2019-blue)
- **Lipschitz Estimates for Conformal Maps from the Unit Disk to Convex Domains**.  *Christopher G. Donohue*.  [[DOI](https://arxiv.org/abs/2106.03808)] [[pdf](https://arxiv.org/pdf/2106.03808)] ![](https://img.shields.io/badge/ICLR2017-yellow)

### Out-of-Distribution Generalization
- **A Baseline for Detecting Misclassified and Out-of-Distribution Examples in Neural Networks**.  *Dan Hendrycks, Kevin Gimpel*.  [[DOI](https://arxiv.org/abs/1610.02136)] [[pdf](https://arxiv.org/pdf/1610.02136)] [[code](https://github.com/hendrycks/error-detection)] ![](https://img.shields.io/badge/ICLR2017-yellow)
- **Deep Anomaly Detection with Outlier Exposure**.  *Dan Hendrycks, Mantas Mazeika, Thomas Dietterich*.  [[DOI](https://arxiv.org/abs/1812.04606)] [[pdf](https://arxiv.org/pdf/1812.04606)] [[code](https://github.com/hendrycks/outlier-exposure)] ![](https://img.shields.io/badge/ICLR2019-yellow)
- **Generalized Out-of-Distribution Detection: A Survey**.  *Jingkang Yang, Kaiyang Zhou, Yixuan Li, Ziwei Liu*.  [[DOI](https://dl.acm.org/doi/abs/10.1007/s11263-024-02117-4)] [[pdf](https://arxiv.org/pdf/2110.11334)] [[code](https://github.com/Jingkang50/OODSurvey)] ![](https://img.shields.io/badge/ACM2024-black)
- **Scaling Out-of-Distribution Detection for Real-World Settings**.  *Dan Hendrycks, Steven Basart, Mantas Mazeika, Andy Zou, Joe Kwon, Mohammadreza Mostajabi, Jacob Steinhardt, Dawn Song*.  [[DOI](https://arxiv.org/abs/1911.11132)] [[pdf](https://arxiv.org/pdf/1911.11132)] [[code](https://github.com/hendrycks/anomaly-seg)] ![](https://img.shields.io/badge/ICML2022-orange)
- **Deep Feature Deblurring Diffusion for Detecting Out-of-Distribution Objects**.  *Aming Wu, Da Chen, Cheng Deng*.  [[DOI](https://ieeexplore.ieee.org/document/10376741)] [[pdf](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_Deep_Feature_Deblurring_Diffusion_for_Detecting_Out-of-Distribution_Objects_ICCV_2023_paper.pdf)] [[code](https://github.com/AmingWu/DFDD-OOD)] ![](https://img.shields.io/badge/ICCV2023-blue)

### Multimodal Generalization


## Applications Systems and Benchmarks

### Camera Trap
- **Automatically identifying, counting, and describing wild animals in camera-trap images with deep learning**.  *Mohammed Sadegh Norouzzadeh, Anh Nguyen, Margaret Kosmala, Ali Swanson, Meredith Palmer, Craig Packer, Jeff Clune*.  [[DOI](https://arxiv.org/abs/1703.05830)] [[pdf](https://arxiv.org/pdf/1703.05830)] ![](https://img.shields.io/badge/arXiv2017-red)
- **Removing Human Bottlenecks in Bird Classification Using Camera Trap Images and Deep Learning**.  *Carl Chalmers, Paul Fergus, Serge Wich, Steven N Longmore, Naomi Davies Walsh, Philip Stephens, Chris Sutherland, Naomi Matthews, Jens Mudde, Amira Nuseibeh*.  [[DOI](https://www.mdpi.com/2072-4292/15/10/2638)] [[pdf](https://arxiv.org/pdf/2305.02097)]  ![](https://img.shields.io/badge/MDPI2023-purple)
- **DeepWILD: Wildlife Identification, Localisation and estimation on camera trap videos using Deep learning**.  *Fanny Simões, Charles Bouveyron, Frédéric Precioso*.  [[DOI](https://www.sciencedirect.com/science/article/abs/pii/S1574954123001243?via%3Dihub)] ![](https://img.shields.io/badge/ScienceDirect2023-orange)
- **An evaluation of platforms for processing camera-trap data using artificial intelligence**.  *Juliana Vélez, William McShea, Hila Shamon, Paula J. Castiblanco-Camacho, Michael A. Tabak, Carl Chalmers, Paul Fergus, John Fieberg*.  [[DOI](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.14044)] [[pdf](https://besjournals.onlinelibrary.wiley.com/doi/epdf/10.1111/2041-210X.14044)] ![](https://img.shields.io/badge/BESJournals2022-green)
- **Automated wildlife image classification: An active learning tool for ecological applications**.  *Ludwig Bothmann, Lisa Wimmer, Omid Charrakh , Tobias Weber, Hendrik Edelhoff, Wibke Peters, Hien Nguyen, Caryl Benjamin, Annette Menzel*.  [[DOI](https://www.sciencedirect.com/science/article/abs/pii/S1574954123002601)] ![](https://img.shields.io/badge/ScienceDirect2023-orange)

### Ecological Monitoring Systems
- **Towards Context-Rich Automated Biodiversity Assessments: Deriving AI-Powered Insights from Camera Trap Data**.  *Paul Fergus, Carl Chalmers, Naomi Matthews, Stuart Nixon, Andre Burger, Oliver Hartley, Chris Sutherland, Xavier Lambin, Steven Longmore, Serge Wich*.  [[DOI](https://arxiv.org/abs/2411.14219)] [[pdf](https://arxiv.org/pdf/2411.14219)] ![](https://img.shields.io/badge/arXiv2024-red)
- **Removing Human Bottlenecks in Bird Classification Using Camera Trap Images and Deep Learning**.  *Carl Chalmers, Paul Fergus, Serge Wich, Steven N Longmore, Naomi Davies Walsh, Philip Stephens, Chris Sutherland, Naomi Matthews, Jens Mudde, Amira Nuseibeh*.  [[DOI](https://arxiv.org/abs/2305.02097)] [[pdf](https://arxiv.org/pdf/2305.02097)] ![](https://img.shields.io/badge/arXiv2023-red)
- **Automated visitor and wildlife monitoring with camera traps and machine learning**.  *Veronika Mitterwallner, Anne Peters, Hendrik Edelhoff, Gregor Mathes, Hien Nguyen, Wibke Peters, Marco Heurich, Manuel J. Steinbauer*.  [[DOI](https://zslpublications.onlinelibrary.wiley.com/doi/10.1002/rse2.367)] [[pdf](https://zslpublications.onlinelibrary.wiley.com/doi/epdf/10.1002/rse2.367)] ![](https://img.shields.io/badge/OUCI2023-green)
- **Trade-off between deep learning for species identification and inference about predator-prey co-occurrence: Reproducible R workflow integrating models in computer vision and ecological statistics**.  *Olivier Gimenez, Maëlis Kervellec, Jean-Baptiste Fanjul, Anna Chaine, Lucile Marescot, Yoann Bollet, Christophe Duchamp*.  [[DOI](https://arxiv.org/abs/2108.11509)] [[pdf](https://arxiv.org/pdf/2108.11509)] ![](https://img.shields.io/badge/arXiv2021-red)


# Supplemental Tools
- **CameraTrapDetectoR**. [[code](https://github.com/CameraTrapDetectoR)]*检测、分类、计数相机陷阱图像中的动物,无代码操作,大规模批处理*.
- **MegaDetector**.[[code](https://github.com/agentmorris/MegaDetector)]*微软社区的主流相机陷阱 AI 模型,很多生态、保护区、政府项目用它来过滤空图像（blank）和标记动物/人/车,它训练于来自全球不同栖息地的大量数据,是当前生态监测中最实用、引用最广的基础工具，被大量论文使用*.
- **AddaxAI**.[[web](https://addaxdatascience.com/addaxai/)]*面向生态专家/研究者的本地运行平台，集成了 MegaDetector，可视化图像分析、标签导出、GPU 加速,支持 human-in-the-loop 校验结果*.
- **Google CameraTrapAI**[[code](https://github.com/google/cameratrapai)]*由 Google 开源的 SpeciesNet + MegaDetector 大规模物种识别组合模型，可用于对图像中的动物进行species级识别,并支持高层次分类（哺乳类、猫科、车辆等）,对生态研究极具价值，可用于大规模长期监测和稀有物种检测实验*.
- **TrapTagger**.[[code](https://github.com/WildEyeConservation/TrapTagger)]*来自 Oxford WildCRU、用于管理、注释、组织大量相机陷阱图像的系统，支持自动分析,混合注释,自己训练 species classifier,大规模多年份生态监测数据处理,物种分类,数据库式管理, Web / AWS 可部署系统*.
- **Animal Detect**.[[web](https://www.animaldetect.com/)]*网页式 workflow 工具，用于上传图像、筛空、分类、导出标注和生成可视化汇总，支持拖拽上传、自动批处理、导出 COCO 格式标注,内置 species 分类,在全球众多保护组织和研究团队中有真实使用案例*
