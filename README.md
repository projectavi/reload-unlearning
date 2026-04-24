# Reload - Partially-Blind Machine Unlearning

[![Paper](https://img.shields.io/badge/Paper-OpenReview-blue)](https://openreview.net/pdf?id=d3R0TF7w5f)
[![Project Page](https://img.shields.io/badge/Project-Website-green)](https://reloadunlearning.github.io/)

This repository contains the code for the paper **[Mitigating Privacy Risk via Forget Set-Free Unlearning](https://openreview.net/pdf?id=d3R0TF7w5f)** published at the 14th International Conference on Learning Representations (ICLR2026).

This work introduces a novel machine unlearning algorithm which achieves *state-of-the-art* performance on classical unlearning, corrective unlearning, and in some entity-unlearning tasks without accessing the "forget set" of data to be forgotten - strengthening privacy guarantees in machine learning deployment.

This repository is organized into three main folders, each corresponding to a different unlearning scenario explored in the paper, along with their respective experimental settings and implementations. These folders are heavily derived from the repositories of [Corrective Unlearning](https://github.com/drimpossible/corrective-unlearning-bench), [SalUn](https://github.com/OPTML-Group/Unlearn-Saliency), and [Large Language Model Unlearning via Embedding-Corrupted Prompts](https://github.com/chrisliu298/llm-unlearn-eco). Huge thanks to the authors of these works for enabling downstream research through open-source :)

## 📄 Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{newatia2026mitigating,
  title     = {Mitigating Privacy Risk via Forget Set-Free Unlearning},
  author    = {Newatia, Aviraj and Cooper, Michael and Nguyen, Viet and Krishnan, Rahul G},
  booktitle = {Proceedings of the 14th International Conference on Learning Representations (ICLR)},
  year      = {2026},
  url       = {https://openreview.net/forum?id=d3R0TF7w5f}
}
