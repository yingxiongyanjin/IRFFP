# 关于arXiv

本项目预期发布两篇arXiv论文（关于如何利用人工智能技术和实时气象数据实现实时林火发生预测以及如何将其应用到林火预警系统中推动林火预警系统向成本更低、空间覆盖更广、实时化、智能化的方向发展）。但由于arXiv的[背书制度（endorsements policy）](https://info.arxiv.org/help/endorsement.html)，后续可能选择其他平台。

## arXiv平台

> [arXiv](https://arxiv.org/#/) is a curated research-sharing platform open to anyone. As a pioneer in digital open access, arXiv.org now hosts more than two million scholarly articles in eight subject areas, curated by our strong community of volunteer moderators.

简单说arXiv是全球最大的预印本文库，有着巨大的影响力。不过如今也出现了许多类似的平台，例如[ChinaXiv](https://chinaxiv.org/home.htm)、jarXiv、[viXra](https://vixra.org/)等。

## 为什么要发表arXiv论文？

arXiv论文是一种[预印本（Preprint）](https://en.wikipedia.org/wiki/Preprint)论文，在arXiv平台发表论文仅需通过资格认证和arXiv审核，而非严格的[同行评审（Peer review）](https://en.wikipedia.org/wiki/Peer_review)。并且在arXiv平台上发表的论文还被允许投稿到其他正式学术期刊。因此，大多学者发表arXiv论文的主要目的是希望在最短时间内发布最新研究成果，以获取网络首发权。

近些年又出现了一种新趋势，“arXiv投稿论文0费用”是“个体研究人员”眼中的香饽饽，而其巨大的影响力也使得大批企业研究机构、高校实验室选择在arXiv发布成果，其中不乏重磅成果。例如：
1. [Very Deep Convolutional Networks for Large-Scale Image Recognition](http://arxiv.org/abs/1409.1556)
2. [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752)

## 如何发表arXiv论文？

主要分为两个阶段：

**1. arXiv论文准备**

目前arXiv可以接收(La)Tex（源码）、PDF（由google docs等文本编辑器生成，而非由LateX生成的）两种格式。Tex/LaTex是目前的最好选择。

目前arXiv在论文样式上并没有明确规定，部分规定也是只是为了方便解析文件。本项目在`/template`中准备了两种模板（来自Github上的开源项目）：
1. [arxiv-style (base on NeurIPS style)](https://github.com/kourgeorge/arxiv-style)
2. [preprint-template (two-column pattern, base on arxiv-style repository)](https://github.com/brenhinkeller/preprint-template.tex)

相关链接：
1. [ArXiv Paper Submission Preparation](https://info.arxiv.org/help/submit/index.html#submission-preparation)
2. [Latex Tutorials](https://latex-tutorial.com/)
3. [Overleaf's Latex Tutorials (arXiv recommend)](https://info.arxiv.org/help/submit_latex_best_practices.html#learning-latex)
4. [Overleaf's Online Latex Editor](https://www.overleaf.com/)

**2. arXiv论文投稿**

arXiv平台提供了注册作者（preference）、有限第三方（for conference）两种投稿途径。本项目将面临的两个关键步骤：
1. [我们需要获得论文对应分区的资格认定（arXiv背书制度）](https://info.arxiv.org/help/endorsement.html)
2. [arXiv工作人员和版主要对文章进行审核（arXiv审核流程）](https://info.arxiv.org/help/moderation/index.html)

提交入口：http://arxiv.org/submit

相关链接：
1. [ArXiv Paper Submission Guidelines](https://info.arxiv.org/help/submit/index.html#submission-guidelines)
