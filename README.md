# Awesome Embodied Vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> A curated list of embodied vision resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing and [awesome-vln](https://github.com/daqingliu/awesome-vln).

By [Changan Chen](https://changan.io) (changan@cs.utexas.edu), Department of Computer Science at the University of Texas at Austin, with help from [Tushar Nagarajan](https://tushar-n.github.io/) and [Santhosh Kumar Ramakrishnan](https://srama2512.github.io/). If you see papers missing from the list, please send me an email or a pull request (format see [below](#contributing)).

## Table of Content

* [Papers](#papers)
	* [PointGoal Navigation](#pointgoal)
	* [Audio-Visual Navigation](#audiogoal)
	* [ObjectGoal Navigation](#objectgoal)
	* [ImageGoal Navigation](#imagegoal)
	* [Vision-Language Navigation](#vln)
	* [Embodied Question Answering](#eqa)
	* [Multiagent Navigation](#multiagent)
	* [Visual Exploration](#visual_exploration)
	* [Visual Interactions](#visual_interaction)
	* [Rearrangement](#rearrangement)
	* [Sim-to-real](#sim2real)
* [Datasets](#datasets)
* [Simulators](#simulators)
* [MISC](#misc)

## <a name="contributing"></a> Contributing
When sending PRs, please put the new paper at the correct chronological position as the following format: <br>

```
* **Paper Title** <br>
*Author(s)* <br>
Conference, Year. [[Paper]](link) [[Code]](link) [[Website]](link)
```

## <a name="papers"></a> Papers

### <a name="pointgoal"></a> PointGoal Navigation
* **Cognitive Mapping and Planning for Visual Navigation** <br>
*Saurabh Gupta, Varun Tolani, James Davidson, Sergey Levine, Rahul Sukthankar, Jitendra Malik* <br>
CVPR, 2017. [[Paper]](https://arxiv.org/abs/1702.03920)

* **Habitat: A Platform for Embodied AI Research** <br>
*Manolis Savva, Abhishek Kadian, Oleksandr Maksymets, Yili Zhao, Erik Wijmans, Bhavana Jain, Julian Straub, Jia Liu, Vladlen Koltun, Jitendra Malik, Devi Parikh, Dhruv Batra* <br>
ICCV, 2019. [[Paper]](https://arxiv.org/abs/1904.01201) [[Code]](https://github.com/facebookresearch/habitat-api) [[Website]](https://aihabitat.org/)

* **SplitNet: Sim2Sim and Task2Task Transfer for Embodied Visual Navigation** <br>
*Daniel Gordon, Abhishek Kadian, Devi Parikh, Judy Hoffman, Dhruv Batra* <br>
ICCV, 2019. [[Paper]](https://arxiv.org/pdf/1905.07512.pdf) [[Code]](https://github.com/facebookresearch/splitnet)

* **A Behavioral Approach to Visual Navigation with Graph Localization Networks** <br>
*Kevin Chen, Juan Pablo de Vicente, Gabriel Sepulveda, Fei Xia, Alvaro Soto, Marynel Vazquez, Silvio Savarese* <br>
RSS, 2019. [[Paper]](https://arxiv.org/pdf/1903.00445.pdf) [[Code]](https://github.com/kchen92/graphnav) [[Website]](https://graphnav.stanford.edu/)

* **DD-PPO: Learning Near-Perfect PointGoal Navigators from 2.5 Billion Frames** <br>
*Erik Wijmans, Abhishek Kadian, Ari Morcos, Stefan Lee, Irfan Essa, Devi Parikh, Manolis Savva, Dhruv Batra* <br>
ICLR, 2020. [[Paper]](https://arxiv.org/abs/1911.00357) [[Code]](https://github.com/facebookresearch/habitat-api/tree/master/habitat_baselines/rl/ddppo) [[Website]](https://wijmans.xyz/publication/ddppo-2019/)

* **Learning to Explore using Active Neural SLAM** <br>
*Devendra Singh Chaplot, Dhiraj Gandhi, Saurabh Gupta, Abhinav Gupta, Ruslan Salakhutdinov* <br>
ICLR, 2020. [[Paper]](https://openreview.net/pdf?id=HklXn1BKDH) [[Code]](https://github.com/devendrachaplot/Neural-SLAM) [[Website]](https://devendrachaplot.github.io/projects/Neural-SLAM)

* **Auxiliary Tasks Speed Up Learning PointGoal Navigation** <br>
*Joel Ye, Dhruv Batra, Erik Wijmans, Abhishek Das* <br>
CoRL, 2020. [[Paper]](https://arxiv.org/abs/2007.04561) [[Code]](https://github.com/joel99/habitat-pointnav-aux)

* **Occupancy Anticipation for Efficient Exploration and Navigation** <br>
*Santhosh K. Ramakrishnan, Ziad Al-Halah, Kristen Grauman* <br>
ECCV, 2020. [[Paper]](http://vision.cs.utexas.edu/projects/occupancy_anticipation/main.pdf) [[Code]](https://github.com/facebookresearch/OccupancyAnticipation) [[Website]](http://vision.cs.utexas.edu/projects/occupancy_anticipation/)

* **Embodied Visual Navigation with Automatic Curriculum Learning in Real Environments** <br>
*Steven D. Morad, Roberto Mecca, Rudra P.K. Poudel, Stephan Liwicki, Roberto Cipolla* <br>
ICRA, 2021. [[Paper]](https://arxiv.org/pdf/2009.05429.pdf)

* **Differentiable SLAM-Net: Learning Particle SLAM for Visual Navigation** <br>
*Peter Karkus, Shaojun Cai, David Hsu* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2105.07593.pdf) 


### <a name="audiogoal"></a> Audio-Visual Navigation
* **Audio-Visual Embodied Navigation** <br>
*Changan Chen\*, Unnat Jain\*, Carl Schissler, Sebastia Vicenc Amengual Gari, Ziad Al-Halah, Vamsi Krishna Ithapu, Philip Robinson, Kristen Grauman* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/pdf/1912.11474.pdf) [[Website]](http://vision.cs.utexas.edu/projects/audio_visual_navigation/)

* **Look, Listen, and Act: Towards Audio-Visual Embodied Navigation** <br>
*Chuang Gan, Yiwei Zhang, Jiajun Wu, Boqing Gong, Joshua B. Tenenbaum* <br>
ICRA, 2020. [[Paper]](https://arxiv.org/pdf/2012.11583.pdf) [[Website]](http://vision.cs.utexas.edu/projects/semantic_audio_visual_navigation)

* **Learning to Set Waypoints for Audio-Visual Navigation** <br>
*Changan Chen, Sagnik Majumder, Ziad Al-Halah, Ruohan Gao, Santhosh K. Ramakrishnan, Kristen Grauman* <br>
ICLR, 2021. [[Paper]](https://arxiv.org/pdf/2008.09622.pdf) [[Website]](http://vision.cs.utexas.edu/projects/audio_visual_waypoints/)

* **Semantic Audio-Visual Navigation** <br>
*Changan Chen, Ziad Al-Halah, Kristen Grauman* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2008.09622.pdf) [[Website]](http://vision.cs.utexas.edu/projects/audio_visual_waypoints/)


### <a name="objectgoal"></a> ObjectGoal Navigation

* **Cognitive Mapping and Planning for Visual Navigation** <br>
*Saurabh Gupta, Varun Tolani, James Davidson, Sergey Levine, Rahul Sukthankar, Jitendra Malik* <br>
CVPR, 2017. [[Paper]](https://arxiv.org/abs/1702.03920)

* **Visual Semantic Navigation using Scene Priors** <br>
*Wei Yang, Xiaolong Wang, Ali Farhadi, Abhinav Gupta, Roozbeh Mottaghi* <br>
ICLR, 2019. [[Paper]](https://arxiv.org/abs/1810.06543)

* **Visual Representations for Semantic Target Driven Navigation** <br>
*Arsalan Mousavian, Alexander Toshev, Marek Fiser, Jana Kosecka, Ayzaan Wahid, James Davidson* <br>
ICRA, 2019. [[Paper]](https://arxiv.org/pdf/1805.06066.pdf) [[Code]](https://github.com/arsalan-mousavian/Navigation)

* **Learning to Learn How to Learn: Self-Adaptive Visual Navigation Using Meta-Learning** <br>
*Mitchell Wortsman, Kiana Ehsani, Mohammad Rastegari, Ali Farhadi, Roozbeh Mottaghi* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/abs/1812.00971) [[Code]](https://github.com/allenai/savn) [[Website]](https://prior.allenai.org/projects/savn)

* **Bayesian Relational Memory for Semantic Visual Navigation** <br>
*Yi Wu, Yuxin Wu, Aviv Tamar, Stuart Russell, Georgia Gkioxari, Yuandong Tian* <br>
ICCV, 2019. [[Paper]](https://arxiv.org/abs/1909.04306) [[Code]](https://github.com/jxwuyi/HouseNavAgent)

* **Situational Fusion of Visual Representation for Visual Navigation** <br>
*William B. Shen, Danfei Xu, Yuke Zhu, Leonidas J. Guibas, Li Fei-Fei, Silvio Savarese* <br>
ICCV, 2019. [[Paper]](https://arxiv.org/abs/1908.09073)

* **Object Goal Navigation using Goal-Oriented Semantic Exploration** <br>
*Devendra Singh Chaplot, Dhiraj Gandhi, Abhinav Gupta\*, Ruslan Salakhutdinov\** <br>
NeurIPS, 2020. [[Paper]](https://arxiv.org/pdf/2007.00643.pdf) [[Website]](https://devendrachaplot.github.io/projects/semantic-exploration)

* **Learning Object Relation Graph and Tentative Policy for Visual Navigation** <br>
*Heming Du, Xin Yu, Liang Zheng* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2007.11018)

* **Semantic Visual Navigation by Watching YouTube Videos** <br>
*Matthew Chang, Arjun Gupta, Saurabh Gupta* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/pdf/2006.10034.pdf) [[Website]](https://matthewchang.github.io/value-learning-from-videos/)

* **ObjectNav Revisited: On Evaluation of Embodied Agents Navigating to Objects** <br>
*Dhruv Batra, Aaron Gokaslan, Aniruddha Kembhavi, Oleksandr Maksymets, Roozbeh Mottaghi, Manolis Savva, Alexander Toshev, Erik Wijmans* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2006.13171)

* **MultiON: Benchmarking Semantic Map Memory using Multi-Object Navigation** <br>
*Saim Wani\*, Shivansh Patel\*, Unnat Jain\*, Angel X. Chang, Manolis Savva* <br>
NeurIPS, 2020. [[Paper]](https://arxiv.org/abs/2012.03912) [[Code]](https://github.com/saimwani/multiON) [[Website]](https://shivanshpatel35.github.io/multi-ON/)

* **Learning hierarchical relationships for object-goal navigation** <br>
*Yiding Qiu, Anwesan Pal, Henrik I. Christensen* <br>
CoRL, 2020. [[Paper]](https://arxiv.org/abs/2003.06749)

* **VTNet: Visual Transformer Network for Object Goal Navigation** <br>
*Heming Du, Xin Yu, Liang Zheng* <br>
ICLR, 2021. [[Paper]](https://arxiv.org/pdf/2009.07783.pdf)

* **Visual Navigation With Spatial Attention** <br>
*Yiding Qiu, Anwesan Pal, Henrik I. Christensen* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2104.09807.pdf)


### <a name="imagegoal"></a> ImageGoal Navigation

* **Target-driven Visual Navigation in Indoor Scenes using Deep Reinforcement Learning** <br>
*Yuke Zhu, Roozbeh Mottaghi, Eric Kolve, Joseph J. Lim, Abhinav Gupta, Li Fei-Fei, Ali Farhadi* <br>
ICRA, 2017. [[Paper]](https://arxiv.org/abs/1609.05143) [[Website]](https://prior.allenai.org/projects/target-driven-visual-navigation)

* **Semi-Parametric Topological Memory for Navigation** <br>
*Nikolay Savinov\*, Alexey Dosovitskiy\*, Vladlen Koltun* <br>
ICLR, 2018. [[Paper]](https://arxiv.org/pdf/1803.00653.pdf) [[Code]](https://github.com/nsavinov/SPTM) [[Website]](https://sites.google.com/view/SPTM)

* **Neural Topological SLAM for Visual Navigation** <br>
*Devendra Singh Chaplot, Ruslan Salakhutdinov, Abhinav Gupta, Saurabh Gupta* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/pdf/2005.12256.pdf) [[Website]](https://devendrachaplot.github.io/projects/Neural-Topological-SLAM)



### <a name="vln"></a> Vision-Language Navigation

* **Vision-and-Language Navigation: Interpreting Visually-Grounded Navigation Instructions in Real Environments** <br>
*Peter Anderson, Qi Wu, Damien Teney, Jake Bruce, Mark Johnson, Niko Sünderhauf, Ian Reid, Stephen Gould, Anton van den Hengel* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1711.07280) [[Code]](https://github.com/peteanderson80/Matterport3DSimulator) [[Website]](https://bringmeaspoon.org)

* **Look Before You Leap: Bridging Model-Free and Model-Based Reinforcement Learning for Planned-Ahead Vision-and-Language Navigation** <br>
*Xin Wang, Wenhan Xiong, Hongmin Wang, William Yang Wang* <br>
ECCV, 2018. [[Paper]](https://arxiv.org/abs/1803.07729)

* **Mapping Instructions to Actions in 3D Environmentswith Visual Goal Prediction** <br>
*Dipendra Misra, Andrew Bennett, Valts Blukis, Eyvind Niklasson, Max Shatkhin, Yoav Artzi* <br>
EMNLP, 2018. [[Paper]](https://arxiv.org/abs/1809.00786)

* **Speaker-Follower Models for Vision-and-Language Navigation** <br>
*Daniel Fried, Ronghang Hu, Volkan Cirik, Anna Rohrbach, Jacob Andreas, Louis-Philippe Morency, Taylor Berg-Kirkpatrick, Kate Saenko, Dan Klein, Trevor Darrell* <br>
NeurIPS, 2018. [[Paper]](https://arxiv.org/abs/1806.02724) [[Code]](https://github.com/ronghanghu/speaker_follower) [[Website]](http://ronghanghu.com/speaker_follower/)

* **Reinforced Cross-Modal Matching and Self-Supervised Imitation Learning for Vision-Language Navigation** <br>
*Xin Wang, Qiuyuan Huang, Asli Celikyilmaz, Jianfeng Gao, Dinghan Shen, Yuan-Fang Wang, William Yang Wang, Lei Zhang* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/abs/1811.10092)

* **Self-Monitoring Navigation Agent via Auxiliary Progress Estimation** <br>
*Chih-Yao Ma, Jiasen Lu, Zuxuan Wu, Ghassan AlRegib, Zsolt Kira, Richard Socher, Caiming Xiong* <br>
ICLR, 2019. [[Paper]](https://arxiv.org/abs/1901.03035) [[Code]](https://github.com/chihyaoma/selfmonitoring-agent) [[Website]](https://chihyaoma.github.io/project/2018/09/27/selfmonitoring.html)

* **The Regretful Agent: Heuristic-Aided Navigation through Progress Estimation** <br>
*Chih-Yao Ma, Zuxuan Wu, Ghassan AlRegib, Caiming Xiong, Zsolt Kira* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/abs/1903.01602) [[Code]](https://github.com/chihyaoma/regretful-agent) [[Website]](https://chihyaoma.github.io/project/2019/02/25/regretful.html)

* **TOUCHDOWN: Natural Language Navigation and Spatial Reasoning in Visual Street Environments** <br>
*Howard Chen, Alane Suhr, Dipendra Misra, Noah Snavely, Yoav Artzi* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/pdf/1811.12354.pdf) [[Code]](https://github.com/lil-lab/touchdown)

* **Tactical Rewind: Self-Correction via Backtracking in Vision-and-Language Navigation** <br>
*Liyiming Ke, Xiujun Li, Yonatan Bisk, Ari Holtzman, Zhe Gan, Jingjing Liu, Jianfeng Gao, Yejin Choi, Siddhartha Srinivasa* <br>
CVPR, 2019. [[Paper]](http://arxiv.org/abs/1903.02547) [[Code]](https://github.com/Kelym/FAST) [[Video]](https://www.youtube.com/watch?v=AD9TNohXoPA)

* **Vision-based Navigation with Language-based Assistance via Imitation Learning with Indirect Intervention** <br>
*Khanh Nguyen, Debadeepta Dey, Chris Brockett, Bill Dolan* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/abs/1909.01871) [[Code]](https://github.com/khanhptnk/hanna) [[Video]](https://youtu.be/18P94aaaLKg)

* **Help, Anna! Visual Navigation with Natural Multimodal Assistance via Retrospective Curiosity-Encouraging Imitation Learning** <br>
*Khanh Nguyen, Hal Daumé III* <br>
EMNLP, 2019. [[Paper]](https://arxiv.org/abs/1812.04155) [[Code]](https://github.com/debadeepta/vnla) [[Video]](https://youtu.be/Vp6C29qTKQ0)

* **Chasing Ghosts: Instruction Following as Bayesian State Tracking** <br>
*Peter Anderson, Ayush Shrivastava, Devi Parikh, Dhruv Batra, Stefan Lee* <br>
NeurIPS, 2019. [[Paper]](https://arxiv.org/abs/1907.02022) [[Code]](https://github.com/batra-mlp-lab/vln-chasing-ghosts) [[Video]](https://www.youtube.com/watch?v=eoGbescCNP0)

* **Embodied Vision-and-Language Navigation with Dynamic Convolutional Filters** <br>
*Federico Landi, Lorenzo Baraldi, Massimiliano Corsini, Rita Cucchiara* <br>
BMVC, 2019. [[Paper]](https://arxiv.org/abs/1907.02985) [[Code]](https://github.com/aimagelab/DynamicConv-agent)

* **Transferable Representation Learning in Vision-and-Language Navigation** <br>
*Haoshuo Huang, Vihan Jain, Harsh Mehta, Alexander Ku, Gabriel Magalhaes, Jason Baldridge, Eugene Ie* <br>
ICCV, 2019. [[Paper]](https://arxiv.org/abs/1908.03409)

* **Unsupervised Reinforcement Learning of Transferable Meta-Skills for Embodied Navigation** <br>
*Juncheng Li, Xin Wang, Siliang Tang, Haizhou Shi, Fei Wu, Yueting Zhuang, William Yang Wang* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/abs/1911.07450)

* **Vision-Language Navigation with Self-Supervised Auxiliary Reasoning Tasks** <br>
*Fengda Zhu, Yi Zhu, Xiaojun Chang, Xiaodan Liang* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/abs/1911.07883)

* **Perceive, Transform, and Act: Multi-Modal Attention Networks for Vision-and-Language Navigation** <br>
*Federico Landi, Lorenzo Baraldi, Marcella Cornia, Massimiliano Corsini, Rita Cucchiara* <br>
arXiv, 2019. [[Paper]](https://arxiv.org/abs/1911.12377) [[Code]](https://github.com/aimagelab/perceive-transform-and-act)

* **Just Ask: An Interactive Learning Framework for Vision and Language Navigation** <br>
*Ta-Chung Chi, Mihail Eric, Seokhwan Kim, Minmin Shen, Dilek Hakkani-tur* <br>
AAAI, 2020. [[Paper]](https://arxiv.org/abs/1912.00915)

* **Towards Learning a Generic Agent for Vision-and-Language Navigation via Pre-training** <br>
*Weituo Hao, Chunyuan Li, Xiujun Li, Lawrence Carin, Jianfeng Gao* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/abs/2002.10638) [[Code]](https://github.com/weituo12321/PREVALENT)

* **Environment-agnostic Multitask Learning for Natural Language Grounded Navigation** <br>
*Xin Wang, Vihan Jain, Eugene Ie, William Yang Wang, Zornitsa Kozareva, Sujith Ravi* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2003.00443)

* **Counterfactual Vision-and-Language Navigation via Adversarial Path Sampling** <br>
*Tsu-Jui Fu, Xin Wang, Matthew Peterson, Scott Grafton, Miguel Eckstein, William Yang Wang* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/1911.07308)

* **Multi-View Learning for Vision-and-Language Navigation** <br>
*Qiaolin Xia, Xiujun Li, Chunyuan Li, Yonatan Bisk, Zhifang Sui, Jianfeng Gao, Yejin Choi, Noah A. Smith* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2003.00857)

* **Vision-Dialog Navigation by Exploring Cross-modal Memory** <br>
*Yi Zhu, Fengda Zhu, Zhaohuan Zhan, Bingqian Lin, Jianbin Jiao, Xiaojun Chang, Xiaodan Liang* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/abs/2003.06745) [[Code]](https://github.com/yeezhu/CMN.pytorch)

* **Take the Scenic Route: Improving Generalization in Vision-and-Language Navigation** <br>
*Felix Yu, Zhiwei Deng, Karthik Narasimhan, Olga Russakovsky* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2003.14269)

* **Sub-Instruction Aware Vision-and-Language Navigation** <br>
*Yicong Hong, Cristian Rodriguez-Opazo, Qi Wu, Stephen Gould* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2004.02707)

* **Beyond the Nav-Graph: Vision-and-Language Navigation in Continuous Environments** <br>
*Jacob Krantz, Erik Wijmans, Arjun Majumdar, Dhruv Batra, Stefan Lee* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2004.02857) [[Code]](https://github.com/jacobkrantz/VLN-CE) [[Website]](https://jacobkrantz.github.io/vlnce)

* **Counterfactual Vision-and-Language Navigation via Adversarial Path Sampling** <br>
*Tsu-Jui Fu, Xin Eric Wang, Matthew Peterson, Scott Grafton, Miguel Eckstein, William Yang Wang* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/1911.07308) [[Code]](https://github.com/jacobkrantz/VLN-CE) [[Website]](https://jacobkrantz.github.io/vlnce)

* **Improving Vision-and-Language Navigation with Image-Text Pairs from the Web** <br>
*Arjun Majumdar, Ayush Shrivastava, Stefan Lee, Peter Anderson, Devi Parikh, Dhruv Batra* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2004.14973)

* **Soft Expert Reward Learning for Vision-and-Language Navigation** <br>
*Hu Wang, Qi Wu, Chunhua Shen* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2007.10835)

* **Active Visual Information Gathering for Vision-Language Navigation** <br>
*Hanqing Wang, Wenguan Wang, Tianmin Shu, Wei Liang, Jianbing Shen* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2007.08037)  [[Code]](https://github.com/HanqingWangAI/Active_VLN)

* **Environment-agnostic Multitask Learning for Natural Language Grounded Navigation** <br>
*Xin Eric Wang, Vihan Jain, Eugene Ie, William Yang Wang, Zornitsa Kozareva, Sujith Ravi* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2003.00443)

* **Language and Visual Entity Relationship Graph for Agent Navigation** <br>
*Yicong Hong, Cristian Rodriguez, Yuankai Qi, Qi Wu, Stephen Gould* <br>
NeurIPS, 2020. [[Paper]](https://arxiv.org/abs/2010.09304) [[Code]](https://github.com/YicongHong/Entity-Graph-VLN)

* **Counterfactual Vision-and-Language Navigation: Unravelling the Unseen** <br>
*Amin Parvaneh, Ehsan Abbasnejad, Damien Teney, Javen Qinfeng Shi, Anton van den Hengel* <br>
NeurIPS, 2020. [[Paper]](https://proceedings.neurips.cc/paper/2020/file/39016cfe079db1bfb359ca72fcba3fd8-Paper.pdf)

* **Evolving Graphical Planner: Contextual Global Planning for Vision-and-Language Navigation** <br>
*Zhiwei Deng, Karthik Narasimhan, Olga Russakovsky* <br>
NeurIPS, 2020. [[Paper]](https://proceedings.neurips.cc/paper/2020/file/eddb904a6db773755d2857aacadb1cb0-Paper.pdf)

* **Generative Language-Grounded Policy in Vision-and-Language Navigation with Bayes' Rule** <br>
*Shuhei Kurita, Kyunghyun Cho* <br>
ICLR, 2021. [[Paper]](https://arxiv.org/pdf/2009.07783.pdf)

* **Hierarchical Cross-Modal Agent for Robotics Vision-and-Language Navigation** <br>
*Muhammad Zubair Irshad, Chih-Yao Ma, Zsolt Kira* <br>
ICRA, 2021. [[Paper]](https://arxiv.org/abs/2104.10674) [[Code]](https://github.com/GT-RIPL/robo-vln) [[Website]](https://zubair-irshad.github.io/projects/robo-vln.html) [[Video]](https://www.youtube.com/watch?v=y16x9n_zP_4)

* **VLN BERT: A Recurrent Vision-and-Language BERT for Navigation** <br>
*Yicong Hong, Qi Wu, Yuankai Qi, Cristian Rodriguez-Opazo, Stephen Gould* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/abs/2011.13922) [[Code]](https://github.com/YicongHong/Recurrent-VLN-BERT)

* **Structured Scene Memory for Vision-Language Navigation** <br>
*Yicong Hong, Qi Wu, Yuankai Qi, Cristian Rodriguez-Opazo, Stephen Gould* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2103.03454.pdf) [[Code]](https://github.com/HanqingWangAI/SSM-VLN)

* **Topological Planning With Transformers for Vision-and-Language Navigation** <br>
*Kevin Chen, Junshen K. Chen, Jo Chuang, Marynel Vázquez, Silvio Savarese* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2012.05292.pdf)

* **SOON: Scenario Oriented Object Navigation With Graph-Based Exploration** <br>
*Fengda Zhu, Xiwen Liang, Yi Zhu, Qizhi Yu, Xiaojun Chang, Xiaodan Liang* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2103.17138.pdf)

* **Room-and-Object Aware Knowledge Reasoning for Remote Embodied Referring Expression** <br>
*Chen Gao, Jinyu Chen, Si Liu, Luting Wang, Qiong Zhang, Qi Wu* <br>
CVPR, 2021. [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Gao_Room-and-Object_Aware_Knowledge_Reasoning_for_Remote_Embodied_Referring_Expression_CVPR_2021_paper.pdf)

* **Scene-Intuitive Agent for Remote Embodied Visual Grounding** <br>
*Xiangru Lin, Guanbin Li, Yizhou Yu* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2103.12944.pdf)

### <a name="multiagent"></a> Multiagent Navigation
* **Two Body Problem: Collaborative Visual Task Completion** <br>
*Unnat Jain\*, Luca Weihs\*, Eric Kolve, Mohammad Rastegari, Svetlana Lazebnik, Ali Farhadi, Alexander Schwing, Aniruddha Kembhavi* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/pdf/1904.05879.pdf) [[Website]](https://prior.allenai.org/projects/two-body-problem)

* **A Cordial Sync: Going Beyond Marginal Policies For Multi-Agent Embodied Tasks** <br>
*Unnat Jain\*, Luca Weihs\*, Eric Kolve, Ali Farhadi, Svetlana Lazebnik, Aniruddha Kembhavi, Alexander Schwing* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2007.04979) [[Code]](https://github.com/allenai/cordial-sync) [[Website]](https://unnat.github.io/cordial-sync/)


### <a name="visual_exploration"></a> Visual Exploration
* **Curiosity-driven Exploration by Self-supervised Prediction** <br>
*Deepak Pathak, Pulkit Agrawal, Alexei A. Efros, Trevor Darrell* <br>
ICML, 2017. [[Paper]](https://arxiv.org/pdf/1705.05363.pdf) [[Code]](https://github.com/pathak22/noreward-rl) [[Website]](https://pathak22.github.io/noreward-rl/)

* **Learning to Look Around: Intelligently Exploring Unseen Environments for Unknown Tasks** <br>
*Dinesh Jayaraman, Kristen Grauman* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1709.00507)

* **Sidekick Policy Learning for Active Visual Exploration** <br>
*Santhosh K. Ramakrishnan, Kristen Grauman* <br>
ECCV, 2018. [[Paper]](https://arxiv.org/abs/1807.11010) [[Code]](https://github.com/srama2512/sidekicks) [[Website]](http://vision.cs.utexas.edu/projects/sidekicks/)

* **Learning Exploration Policies for Navigation** <br>
*Tao Chen, Saurabh Gupta, Abhinav Gupta* <br>
ICLR, 2019. [[Paper]](https://openreview.net/pdf?id=SyMWn05F7) [[Code]](https://github.com/taochenshh/exp4nav) [[Website]](https://sites.google.com/view/exploration-for-nav/)

* **Episodic Curiosity through Reachability** <br>
*Nikolay Savinov, Anton Raichuk, Damien Vincent, Raphael Marinier, Marc Pollefeys, Timothy Lillicrap, Sylvain Gelly* <br>
ICLR, 2019. [[Paper]](https://openreview.net/pdf?id=SkeK3s0qKQ) [[Code]](https://github.com/google-research/episodic-curiosity) [[Website]](https://sites.google.com/view/episodic-curiosity)

* **Emergence of Exploratory Look-Around Behaviors through Active Observation Completion** <br>
*Santhosh K. Ramakrishnan\*, Dinesh Jayaraman\*, Kristen Grauman* <br>
Science Robotics, 2019. [[Paper]](https://arxiv.org/pdf/1906.11407.pdf) [[Code]](https://github.com/srama2512/visual-exploration) [[Website]](http://vision.cs.utexas.edu/projects/visual-exploration/)

* **Scene Memory Transformer for Embodied Agents in Long-Horizon Tasks** <br>
*Kuan Fang, Alexander Toshev, Li Fei-Fei, Silvio Savarese* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/pdf/1903.03878.pdf) [[Website]](https://sites.google.com/view/scene-memory-transformer)

* **Learning to Explore using Active Neural SLAM** <br>
*Devendra Singh Chaplot, Dhiraj Gandhi, Saurabh Gupta, Abhinav Gupta, Ruslan Salakhutdinov* <br>
ICLR, 2020. [[Paper]](https://openreview.net/pdf?id=HklXn1BKDH) [[Code]](https://github.com/devendrachaplot/Neural-SLAM) [[Website]](https://devendrachaplot.github.io/projects/Neural-SLAM)

* **Semantic Curiosity for Active Visual Learning** <br>
*Devendra Singh Chaplot, Helen Jiang, Saurabh Gupta, Abhinav Gupta* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/pdf/2006.09367.pdf) [[Website]](https://devendrachaplot.github.io/projects/SemanticCuriosity)

* **See, Hear, Explore: Curiosity via Audio-Visual Association** <br>
*Victoria Dean, Shubham Tulsiani, Abhinav Gupta* <br>
arXiv, 2020. [[Paper]](https://vdean.github.io/resources/audio-curiosity2020.pdf) [[Website]](https://vdean.github.io/audio-curiosity.html)

* **Occupancy Anticipation for Efficient Exploration and Navigation** <br>
*Santhosh K. Ramakrishnan, Ziad Al-Halah, Kristen Grauman* <br>
ECCV, 2020. [[Paper]](http://vision.cs.utexas.edu/projects/occupancy_anticipation/main.pdf) [[Code]](https://github.com/facebookresearch/OccupancyAnticipation) [[Website]](http://vision.cs.utexas.edu/projects/occupancy_anticipation/)


### <a name="eqa"></a> Embodied Question Answering
* **Embodied Question Answering** <br>
*Abhishek Das, Samyak Datta, Georgia Gkioxari, Stefan Lee, Devi Parikh, Dhruv Batra* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1711.11543) [[Code]](https://github.com/facebookresearch/EmbodiedQA) [[Website]](https://embodiedqa.org/)

* **Multi-Target Embodied Question Answering** <br>
*Licheng Yu, Xinlei Chen, Georgia Gkioxari, Mohit Bansal, Tamara L. Berg, Dhruv Batra* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/abs/1904.04686)

* **Embodied Question Answering in Photorealistic Environments with Point Cloud Perception** <br>
*Erik Wijmans\*, Samyak Datta\*, Oleksandr Maksymets\*, Abhishek Das, Georgia Gkioxari, Stefan Lee, Irfan Essa, Devi Parikh, Dhruv Batra* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/abs/1904.03461)



### <a name="visual_interaction"></a> Visual Interactions
* **Visual Semantic Planning using Deep Successor Representations** <br>
*Yuke Zhu, Daniel Gordon, Eric Kolve, Dieter Fox, Li Fei-Fei, Abhinav Gupta, Roozbeh Mottaghi, Ali Farhadi* <br>
ICCV, 2017. [[Paper]](https://arxiv.org/abs/1705.08080)

* **IQA: Visual Question Answering in Interactive Environments** <br>
*Daniel Gordon, Aniruddha Kembhavi, Mohammad Rastegari, Joseph Redmon, Dieter Fox, and Ali Farhadi* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1712.03316) [[Code]](https://github.com/danielgordon10/thor-iqa-cvpr-2018) [[Website]](https://prior.allenai.org/projects/iqa)

* **ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks** <br>
*Mohit Shridhar, Jesse Thomason, Daniel Gordon, Yonatan Bisk, Winson Han, Roozbeh Mottaghi, Luke Zettlemoyer, Dieter Fox* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/abs/1912.01734) [[Code]](https://github.com/askforalfred/alfred) [[Website]](https://askforalfred.com/)

* **Learning About Objects by Learning to Interact with Them** <br>
*Martin Lohmann, Jordi Salvador, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
NeurIPS, 2020. [[Paper]](https://arxiv.org/abs/2006.09306)

* **Learning Affordance Landscapes for Interaction Exploration in 3D Environments** <br>
*Tushar Nagarajan, Kristen Grauman* <br>
NeurIPS, 2020. [[Paper]](https://proceedings.neurips.cc/paper/2020/file/15825aee15eb335cc13f9b559f166ee8-Paper.pdf)

* **ALFWorld: Aligning Text and Embodied Environments for Interactive Learning** <br>
*Mohit Shridhar, Xingdi Yuan, Marc-Alexandre Côté, Yonatan Bisk, Adam Trischler, Matthew Hausknecht* <br>
ICLR, 2021. [[Paper]](https://arxiv.org/pdf/2010.03768.pdf) [[Code]](https://github.com/alfworld/alfworld) [[Website]](https://alfworld.github.io/)

* **Learning Generalizable Visual Representations via Interactive Gameplay** <br>
*Luca Weihs, Aniruddha Kembhavi, Kiana Ehsani, Sarah M Pratt, Winson Han, Alvaro Herrasti, Eric Kolve, Dustin Schwenk, Roozbeh Mottaghi, Ali Farhadi* <br>
ICLR, 2021. [[Paper]](https://arxiv.org/pdf/1912.08195.pdf)

* **Pushing It Out of the Way: Interactive Visual Navigation** <br>
*Kuo-Hao Zeng, Luca Weihs, Ali Farhadi, Roozbeh Mottaghi* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2104.14040.pdf) [[Code]](https://github.com/KuoHaoZeng/Interactive_Visual_Navigation) [[Website]](https://prior.allenai.org/projects/interactive-visual-navigation)

* **ManipulaTHOR: A Framework for Visual Object Manipulation** <br>
*Kiana Ehsani, Winson Han, Alvaro Herrasti, Eli VanderBilt, Luca Weihs, Eric Kolve, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2104.11213.pdf) [[Code]](https://github.com/allenai/manipulathor) [[Website]](https://ai2thor.allenai.org/manipulathor/)

### <a name="rearrangement"></a> Rearrangement
* **Visual Room Rearrangement** <br>
*Luca Weihs, Matt Deitke, Aniruddha Kembhavi, and Roozbeh Mottaghi* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/abs/1705.08080) [[Code]](https://github.com/allenai/ai2thor-rearrangement) [[Website]](https://ai2thor.allenai.org/rearrangement)

* **Rearrangement: A Challenge for Embodied AI** <br>
*Dhruv Batra, Angel X. Chang, Sonia Chernova, Andrew J. Davison, Jia Deng, Vladlen Koltun, Sergey Levine, Jitendra Malik, Igor Mordatch, Roozbeh Mottaghi, Manolis Savva, Hao Su* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2011.01975)


### <a name="sim2real"></a> Sim-to-real
* **Domain Randomization for Transferring Deep Neural Networks from Simulation to the Real World** <br>
*Josh Tobin, Rachel Fong, Alex Ray, Jonas Schneider, Wojciech Zaremba, Pieter Abbeel* <br>
IROS, 2017. [[Paper]](https://arxiv.org/abs/1703.06907)

* **Sim-to-Real Transfer for Vision-and-Language Navigation** <br>
*Peter Anderson, Ayush Shrivastava, Joanne Truong, Arjun Majumdar, Devi Parikh, Dhruv Batra, Stefan Lee* <br>
CoRL, 2020. [[Paper]](https://arxiv.org/abs/2011.03807)

## <a name="datasets"></a> Datasets
* **A Dataset for Developing and Benchmarking Active Vision** <br>
*Phil Ammirato, Patrick Poirson, Eunbyung Park, Jana Kosecka, Alexander C. Berg* <br>
ICRA, 2017. [[Paper]](https://www.cs.unc.edu/~ammirato/active_vision_dataset_website/icra-rohit-paper.pdf) [[Code]](https://github.com/ammirato/active_vision_dataset_processing) [[Website]](https://www.cs.unc.edu/~ammirato/active_vision_dataset_website/)

* **AI2-THOR: An Interactive 3D Environment for Visual AI** <br>
*Eric Kolve, Roozbeh Mottaghi, Winson Han, Eli VanderBilt, Luca Weihs, Alvaro Herrasti, Daniel Gordon, Yuke Zhu, Abhinav Gupta, Ali Farhadi* <br>
arXiv, 2017. [[Paper]](https://arxiv.org/abs/1712.05474) [[Code]](https://github.com/allenai/ai2thor) [[Website]](https://ai2thor.allenai.org/)

* **Matterport3D: Learning from RGB-D Data in Indoor Environments** <br>
*Angel Chang, Angela Dai, Thomas Funkhouser, Maciej Halber, Matthias Nießner, Manolis Savva, Shuran Song, Andy Zeng, Yinda Zhang* <br>
3DV, 2017. [[Paper]](https://arxiv.org/pdf/1709.06158.pdf) [[Code]](https://github.com/niessner/Matterport) [[Website]](https://niessner.github.io/Matterport/)

* **Gibson Env: Real-World Perception for Embodied Agents** <br>
*Fei Xia, Amir Zamir, Zhi-Yang He, Alexander Sax, Jitendra Malik, Silvio Savarese* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1808.10654) [[Code]](https://github.com/StanfordVL/GibsonEnv) [[Website]](http://gibsonenv.stanford.edu/)

* **The Replica Dataset: A Digital Replica of Indoor Spaces** <br>
*Julian Straub, Thomas Whelan, Lingni Ma, Yufan Chen, Erik Wijmans, Simon Green, Jakob J. Engel, Raul Mur-Artal, Carl Ren, Shobhit Verma, Anton Clarkson, Mingfei Yan, Brian Budge, Yajie Yan, Xiaqing Pan, June Yon, Yuyang Zou, Kimberly Leon, Nigel Carter, Jesus Briales, Tyler Gillingham, Elias Mueggler, Luis Pesqueira, Manolis Savva, Dhruv Batra, Hauke M. Strasdat, Renzo De Nardi, Michael Goesele, Steven Lovegrove, Richard Newcombe* <br>
arXiV, 2019. [[Paper]](https://arxiv.org/pdf/1906.05797.pdf) [[Code]](https://github.com/facebookresearch/Replica-Dataset)

* **Actionet: An Interactive End-to-End Platform for Task-Based Data Collection and Augmentation in 3D Environments** <br>
*Jiafei Duan, Samson Yu, Hui Li Tan, Cheston Tan* <br>
ICIP, 2020. [[Paper]](https://arxiv.org/pdf/2010.01357.pdf) [[Code]](https://github.com/SamsonYuBaiJian/actionet)


## <a name="simulators"></a> Simulators
* **AI2-THOR: An Interactive 3D Environment for Visual AI** <br>
*Eric Kolve, Roozbeh Mottaghi, Winson Han, Eli VanderBilt, Luca Weihs, Alvaro Herrasti, Daniel Gordon, Yuke Zhu, Abhinav Gupta, Ali Farhadi* <br>
arXiv, 2017. [[Paper]](https://arxiv.org/abs/1712.05474) [[Code]](https://github.com/allenai/ai2thor) [[Website]](https://ai2thor.allenai.org/)

* **Building Generalizable Agents with a Realistic and Rich 3D Environment (House3D)** <br>
*Yi Wu, Yuxin Wu, Georgia Gkioxari, Yuandong Tian* <br>
arXiv, 2018. [[Paper]](https://arxiv.org/pdf/1801.02209.pdf) [[Code]](https://github.com/facebookresearch/House3D)

* **CHALET: Cornell House Agent Learning Environment** <br>
*Claudia Yan, Dipendra Misra, Andrew Bennett, Aaron Walsman, Yonatan Bisk and Yoav Artzi* <br>
arXiv, 2018. [[Paper]](https://arxiv.org/pdf/1801.07357.pdf) [[Code]](https://github.com/facebookresearch/House3D)

* **RoboTHOR: An Open Simulation-to-Real Embodied AI Platform** <br>
*Matt Deitke, Winson Han, Alvaro Herrasti, Aniruddha Kembhavi, Eric Kolve, Roozbeh Mottaghi, Jordi Salvador, Dustin Schwenk, Eli VanderBilt, Matthew Wallingford, Luca Weihs, Mark Yatskar, Ali Farhadi* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/abs/2004.06799) [[Website]](https://github.com/lil-lab/chalet)

* **Gibson Env: Real-World Perception for Embodied Agents** <br>
*Fei Xia, Amir Zamir, Zhi-Yang He, Alexander Sax, Jitendra Malik, Silvio Savarese* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1808.10654) [[Code]](https://github.com/StanfordVL/GibsonEnv) [[Website]](http://gibsonenv.stanford.edu/)

* **Habitat: A Platform for Embodied AI Research** <br>
*Manolis Savva, Abhishek Kadian, Oleksandr Maksymets, Yili Zhao, Erik Wijmans, Bhavana Jain, Julian Straub, Jia Liu, Vladlen Koltun, Jitendra Malik, Devi Parikh, Dhruv Batra* <br>
ICCV, 2019. [[Paper]](https://arxiv.org/abs/1904.01201) [[Code]](https://github.com/facebookresearch/habitat-api) [[Website]](https://aihabitat.org/)

* **VirtualHome: Simulating Household Activities via Programs** <br>
*Xavier Puig\*, Kevin Ra\*, Marko Boben\*, Jiaman Li, Tingwu Wang, Sanja Fidler, Antonio Torralba* <br>
CVPR, 2018. [[Paper]](http://virtual-home.org/paper/virtualhome.pdf) [[Code]](https://github.com/xavierpuigf/virtualhome) [[Website]](http://virtual-home.org/)

* **ThreeDWorld: A Platform for Interactive Multi-Modal Physical Simulation** <br>
*Chuang Gan, Jeremy Schwartz, Seth Alter, Martin Schrimpf, James Traer, Julian De Freitas, Jonas Kubilius, Abhishek Bhandwaldar, Nick Haber, Megumi Sano, Kuno Kim, Elias Wang, Damian Mrowca, Michael Lingelbach, Aidan Curtis, Kevin Feigelis, Daniel M. Bear, Dan Gutfreund, David Cox, James J. DiCarlo, Josh McDermott, Joshua B. Tenenbaum, Daniel L.K. Yamins*<br>
arXiv, 2020. [[Paper]](https://arxiv.org/pdf/2007.04954.pdf) [[Code]](https://github.com/threedworld-mit/tdw) [[Website]](http://www.threedworld.org/)

* **ALFWorld: Aligning Text and Embodied Environments for Interactive Learning** <br>
*Mohit Shridhar, Xingdi Yuan, Marc-Alexandre Côté, Yonatan Bisk, Adam Trischler, Matthew Hausknecht*<br>
ICLR, 2021. [[Paper]](https://arxiv.org/abs/2010.03768) [[Code]](https://github.com/alfworld/alfworld) [[Website]](https://alfworld.github.io/)

* **ManipulaTHOR: A Framework for Visual Object Manipulation** <br>
*Kiana Ehsani, Winson Han, Alvaro Herrasti, Eli VanderBilt, Luca Weihs, Eric Kolve, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2104.11213.pdf) [[Code]](https://github.com/allenai/manipulathor) [[Website]](https://ai2thor.allenai.org/manipulathor/)

## <a name="misc"></a> MISC
* **Visual Learning and Embodied Agents in Simulation Environments Workshop** <br>
ECCV, 2018. [[website]](https://eccv18-vlease.github.io/)

* **Embodied-AI Workshop** <br>
CVPR, 2020/2021. [[website]](https://embodied-ai.org/#overview)

* **Gibson Sim2Real Challenge** <br>
CVPR, 2020. [[website]](http://svl.stanford.edu/igibson/challenge.html)

* **Embodied Vision, Actions & Language Workshop** <br>
ECCV, 2020. [[website]](https://askforalfred.com/EVAL/)

* **Closing the Reality Gap in Sim2Real Transfer for Robotics** <br>
RSS, 2020. [[website]](https://sim2real.github.io/?fbclid=IwAR0fyyc_k8AmmYYRHbJJtjqGonAn1TUhUPWEdEpwpMbuwIkTgxmC13TJjG4)

* **On Evaluation of Embodied Navigation Agents** <br>
*Peter Anderson, Angel Chang, Devendra Singh Chaplot, Alexey Dosovitskiy, Saurabh Gupta, Vladlen Koltun, Jana Kosecka, Jitendra Malik, Roozbeh Mottaghi, Manolis Savva, Amir R. Zamir* <br>
arXiv, 2018. [[Paper]](https://arxiv.org/abs/1807.06757)

* **PyRobot: An Open-source Robotics Framework for Research and Benchmarking** <br>
*Adithya Murali\*, Tao Chen\*, Kalyan Vasudev Alwala\*, Dhiraj Gandhi\*, Lerrel Pinto, Saurabh Gupta, Abhinav Gupta* <br>
arXiv, 2019. [[Paper]](https://arxiv.org/abs/1906.08236) [[Code]](https://github.com/facebookresearch/pyrobot) [[Website]](https://www.pyrobot.org/)

* **A Survey of Embodied AI: From Simulators to Research Tasks** <br>
*Jiafei Duan, Samson Yu, Hui Li Tan, Hongyuan Zhu, Cheston Tan* <br>
arXiv, 2021. [[Paper]](https://arxiv.org/abs/2103.04918)

* **AllenAct: A Framework for Embodied AI Research** <br>
*Luca Weihs, Jordi Salvador, Klemen Kotar, Unnat Jain, Kuo-Hao Zeng, Roozbeh Mottaghi, Aniruddha Kembhavi* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2008.12760) [[Website]](https://allenact.org/)

* **CSAIL Embodied Intelligence Seminar** <br>
[[website]](https://ei.csail.mit.edu/seminars.html)
