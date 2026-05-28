# A Temporal-Spatial-Semantic Consistent Online Incremental UAG Map Construction Framework

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Our Method** is a **temporal-spatial-semantic consistent task-driven 3D Scene Graph (3DSG) construction framework** that extends [Clio](https://github.com/MIT-SPARK/clio) (Maggio et al., ICRA 2024) from a cartography-robotics interdisciplinary perspective. Inspired by thematic cartography principles, this framework addresses the fundamental limitation of existing task-driven mapping methods that rely solely on single-dimensional (semantic) similarity, by jointly modeling **time, space, and semantics** — the three essential dimensions of geographic phenomena — for robust online incremental mapping.

> **Paper Status**: This work is currently in submission status. The complete code and detailed reproduction instructions will be released upon paper acceptance. Stay tuned!

---

## Table of Contents

- [Overview](#overview)
- [Datasets](#datasets)
- [Citation](#citation)
- [License](#license)

---

## Overview

From a cartographic perspective, time, space, and attribute (semantics) constitute the three fundamental dimensions for describing geographic phenomena. Any thematic map is a specific expression of these dimensions and their interrelationships. However, existing robot task-driven mapping frameworks — including the original Clio — typically operate on single-dimensional semantic similarity, leading to two critical challenges.

Our Method addresses these challenges by introducing a **five-module architecture** that integrates cartographic principles into online robotic mapping

## Datasets

The datasets used in our experiments are available for download:

> **Download Link**: [https://www.dropbox.com/scl/fo/5bkv8rsa2xvwmvom6bmza/AOc8VW71kuZCgQjcw_REbWA?rlkey=wx1njghufcxconm1znidc1hgw&st=c809h8h3&dl=0](https://www.dropbox.com/scl/fo/5bkv8rsa2xvwmvom6bmza/AOc8VW71kuZCgQjcw_REbWA?rlkey=wx1njghufcxconm1znidc1hgw&st=c809h8h3&dl=0)

The datasets include synchronized RGB-D streams with pose and timestamp annotations across three real-world indoor environments，Each dataset provides manually annotated 3D bounding boxes as ground truth for task-relevant objects.

---

## Citation

If you use Our Method in your research, please cite both the original Clio work and our enhanced version (citation will be updated upon paper acceptance).

```bibtex
@inproceedings{maggio2024clio,
  title     = {Clio: Real-time Task-Driven Open-Set 3D Scene Graphs},
  author    = {Maggio, Dominic and Chang, Yun and Hughes, Nathan and others},
  booktitle = {IEEE International Conference on Robotics and Automation (ICRA)},
  year      = {2024}
}
```

> ⚠️ **Note**: After paper acceptance, the complete code and detailed reproduction instructions will be released. For inquiries, please open an issue or contact the authors.

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

Copyright (c) Massachusetts Institute of Technology (MIT).

---

**Acknowledgments**: This work builds upon the [Clio](https://github.com/MIT-SPARK/clio) framework developed by the [MIT SPARK Lab](https://sparklab.mit.edu/).
