# SOFI: Sparseness-Optimized Feature Importance
In this paper, we propose a model-agnostic post-hoc explanation procedure devoted to computing feature attribution. The proposed method, termed Sparseness-Optimized Feature Importance (SOFI), entails solving an optimization problem related to the sparseness of feature importance explanations. The intuition behind this property is that the model's performance is severely affected after marginalizing the most important features while remaining largely unaffected after marginalizing the least important ones. Existing post-hoc feature attribution methods do not optimize this property directly but rather implement proxies to obtain this behavior. Numerical simulations using both structured (tabular) and unstructured (image) classification datasets show the superiority of our proposal compared with state-of-the-art feature attribution explanation methods.

## Citation
If you use this code in your research, please cite the following paper:

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

