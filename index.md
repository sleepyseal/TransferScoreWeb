---
layout: project_page
permalink: /

title: Can We Evaluate Domain Adaptation Models Without Target-Domain Labels?
authors:
    Jianfei, Yang, Hanjie, Qian, Yuecong Xu, Kai Wang and Lihua, Xie
affiliations:
    Nanyang Technology University
    National University of Singapore 
paper: https://openreview.net/forum?id=fszrlQ2DuP
code: https://github.com/sleepyseal/TransferScore
video: https://www.youtube.com/results?search_query=turing+machine
---

<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Unsupervised domain adaptation (UDA) involves adapting a model trained on a label-rich source domain to an unlabeled target domain. However, in real-world scenarios, the absence of target-domain labels makes it challenging to evaluate the performance of UDA models. Furthermore, prevailing UDA methods relying on adversarial training and self-training could lead to model degeneration and negative transfer, further exacerbating the evaluation problem. In this paper, we propose a novel metric called the Transfer Score to address these issues. The proposed metric enables the unsupervised evaluation of UDA models by assessing the spatial uniformity of the classifier via model parameters, as well as the transferability and discriminability of deep representations. Based on the metric, we achieve three novel objectives without target-domain labels: (1) selecting the best UDA method from a range of available options, (2) optimizing hyperparameters of UDA models to prevent model degeneration, and (3) identifying which checkpoint of UDA model performs optimally. Our work bridges the gap between data-level UDA research and practical UDA scenarios, enabling a realistic assessment of UDA model performance. We validate the effectiveness of our metric through extensive empirical studies on UDA datasets of different scales and imbalanced distributions. The results demonstrate that our metric robustly achieves the aforementioned goals.
        </div>
    </div>
</div>

---

## Citation
```
@inproceedings{yang2023can,
  title = {Can We Evaluate Domain Adaptation Models Without Target-Domain Labels?},
  author = {Yang, Jianfei and Qian, Hanjie and Xu, Yuecong and Wang, Kai and Xie, Lihua},
  booktitle = {International Conference on Learning Representations},
  Month = {May},
  year = {2024}
}
```
