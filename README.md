# SOFI-Reg: Sparseness-Optimized Feature Importance for Regression Models in Bone Age Assessment

**SOFI-Reg** is a novel extension of **Sparseness-Optimized Feature Importance (SOFI)** specifically designed for **deep regression models**. While the original SOFI framework was developed for image classification tasks, this work adapts and extends the underlying optimization framework to produce faithful feature attribution maps for continuous prediction problems, with a particular focus on **bone age assessment from hand radiographs**.

The proposed approach remains model-agnostic and computes feature importance by solving an optimization problem that directly maximizes the sparsity and faithfulness of the explanation. The central intuition is that masking the most relevant image regions should cause a significant degradation in the predicted bone age, whereas masking irrelevant regions should have little or no effect on the model's output. Unlike existing post-hoc attribution methods, which rely on heuristic approximations of this behavior, **SOFI-Reg explicitly optimizes this objective for regression models**.

This repository contains the implementation of SOFI-Reg, including its adaptation for bone age estimation networks, evaluation protocols, and experiments on hand X-ray datasets. The proposed framework enables quantitative comparison with state-of-the-art explainability methods while providing clinically meaningful visual explanations that highlight the anatomical structures driving bone age predictions.

**Key contributions:**

* A **novel extension of SOFI from classification to regression models**.
* A model-agnostic explainability framework tailored for **bone age assessment**.
* Optimization-based feature attribution that directly enforces sparse and faithful explanations.
* Quantitative and qualitative evaluation against state-of-the-art post-hoc explanation methods for medical image regression.

---

### 📥 Download the Dataset

1. The dataset is provided as **`Data_UCI.zip`** in the TAG section.
2. You can either click on the TAG in the repository or directly use this link:
   [Download Dataset](https://github.com/TeodoroRafael/BAA_data/releases)

---

## Citation
If you use this code in your research, please cite the following papers:

```bibtex
@InProceedings{,
author="",
title="",
booktitle="",
year="2026",
publisher="",
address="",
pages="",
isbn=""
}
```


```bibtex
@InProceedings{10.1007/978-3-031-63797-1_20,
author="Grau, Isel
and N{\'a}poles, Gonzalo",
editor="Longo, Luca
and Lapuschkin, Sebastian
and Seifert, Christin",
title="Sparseness-Optimized Feature Importance",
booktitle="Explainable Artificial Intelligence",
year="2024",
publisher="Springer Nature Switzerland",
address="Cham",
pages="393--415",
isbn="978-3-031-63797-1"
}
```

