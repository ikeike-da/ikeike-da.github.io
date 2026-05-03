---
title: "Natural Evolution Strategy for Mixed-Integer Black-Box Optimization"
date: 2023-07-12
tags: ["black-box optimization", "mixed-integer", "mixed-variable", "evolutionary computation", "CMA-ES", "NES"]
author: ["Koki Ikeda","Isao Ono"]
description: "This paper proposes DX-NES-ICI for mixed-integer black-box optimization. Published in GECCO, 2023."
summary: "This paper proposes DX-NES-ICI, a natural evolution strategy that accounts for implicit constraints and integer variables in mixed-integer black-box optimization. It demonstrates improved performance over CMA-ES w. Margin on benchmark problems, particularly when continuous variables contribute more to the objective function value than integer variables."
# cover:
#     image: "paper1.png"
#     alt: "paper1"
#     relative: true
editPost:
    URL: "https://doi.org/10.1145/3583131.3590518"
    Text: "GECCO'23"
---

---

##### Abstract

This paper proposes a natural evolution strategy (NES) for mixed-integer black-box optimization (MI-BBO) that appears in real-world problems such as hyperparameter optimization of machine learning and materials design. This problem is difficult to optimize because plateaus where the values do not change appear when the integer variables are relaxed to the continuous ones. CMA-ES w. Margin that addresses the plateaus reportedly showed good performance on MI-BBO benchmark problems. However, it has been observed that the search performance of CMA-ES w. Margin deteriorates when continuous variables contribute more to the objective function value than integer ones. In order to address the problem of CMA-ES w. Margin, we propose Distance-weighted eXponential Natural Evolution Strategy taking account of Implicit Constraint and Integer (DX-NES-ICI). We compare the search performance of DX-NES-ICI with that of CMA-ES w. Margin through numerical experiments. As a result, DX-NES-ICI was up to 3.7 times better than CMA-ES w. Margin in terms of a rate of finding the optimal solutions on benchmark problems where continuous variables contribute more to the objective function value than integer ones. DX-NES-ICI also outperformed CMA-ES w. Margin on problems where CMA-ES w. Margin originally showed good performance.

---

##### Citation

Koki Ikeda and Isao Ono. 2023. "Natural Evolution Strategy for Mixed-Integer Black-Box Optimization." In Proceedings of the Genetic and Evolutionary Computation Conference (GECCO '23). Association for Computing Machinery, 831–838. https://doi.org/10.1145/3583131.3590518

```latex
@inproceedings{10.1145/3583131.3590518,
author = {Ikeda, Koki and Ono, Isao},
title = {Natural Evolution Strategy for Mixed-Integer Black-Box Optimization},
year = {2023},
isbn = {9798400701191},
publisher = {Association for Computing Machinery},
url = {https://doi.org/10.1145/3583131.3590518},
doi = {10.1145/3583131.3590518},
booktitle = {Proceedings of the Genetic and Evolutionary Computation Conference},
pages = {831–838},
numpages = {8},
series = {GECCO '23}
}
```

---

##### Related material

+ [Paper](https://doi.org/10.1145/3583131.3590518)
+ [arXiv](https://arxiv.org/abs/2304.10724)
+ [Code](https://github.com/ono-lab/dxnesici)
