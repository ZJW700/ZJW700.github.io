---
permalink: /
title: "Home"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

您好，我是张婧炜，南京航空航天大学研二生。建站记录自己的生活和学习。

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

科研成果
======

论文：MUS-CDB: Mixed Uncertainty Sampling with Class Distribution Balancing for Active Annotation in Aerial Object Detection--在投
------
Recent aerial object detection models rely on a large amount of labeled training data, which requires unaffordable manual labeling costs in large aerial scenes with dense objects. Active learning is effective in reducing the data labeling cost by selectively querying the informative and representative unlabelled samples. However, existing active learning methods are mainly with class-balanced setting and image-based querying for generic object detection tasks, which are less applicable to aerial object detection scenario due to the long-tailed class distribution and dense small objects in aerial scenes. In this paper, we propose a novel active learning method for cost-effective aerial object detection. Specifically, both object-level and image-level informativeness are considered in the object selection to refrain from redundant and myopic querying. Besides, an easy-to-use class-balancing criterion is incorporated to favor the minority objects to alleviate the long-tailed class distribution problem in model training. To fully utilize the queried information, we further devise a training loss to mine the latent knowledge in the undiscovered image regions. Extensive experiments are conducted on the DOTA-v1.0 and DOTA-v2.0 benchmarks to validate the effectiveness of the proposed method. The results show that it can save more than 75% of the labeling cost to reach the same performance compared to the baselines and stateof-the-art active object detection methods. Code is available at https://github.com/ZJW700/MUS-CDB。

专利：一种场景语义引导的遥感目标检测主动采样方法--已受理
------
本发明公开了一种场景语义引导的遥感目标检测主动采样方法。包括：一、构建用于遥感目标检测的网络模型，并进行数据初始化；二、对已标注集进行训练；三、目标检测模型输出对未标注集的预测结果；四、计算未标注集中模型预测对象的信息量；五、利用已标注集中类别分布先验来调整主动学习采样阶段的类别分布；六、对挑选出来的数据进行人工标注并且合并到标注数据集；七、使用新的标记数据集对模型进行微调。八、验证模型在测试集上的性能，根据当前主动学习轮次来判断是否继续下一轮主动学习采样。 
