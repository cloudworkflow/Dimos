# Dimos

This is an implemention for our paper based on Pytorch

Dimos: Diffusion model with unified sequential state space for session-based recommendation

This paper is just accepted by Engineering Applications of Artificial Intelligence.

# Dataset
We provide one dataset: Diginetica. 

The Yoochoose dataset can be found at: https://recsys.acm.org/recsys15/challenge

The Retailrocket dataset can be found at: https://www.kaggle.com/retailrocket/ecommerce-dataset

# Example to run the codes

1. Environment: I have tested this code with python=3.8.10 Pytorch=2.0.0 CUDA=11.8

git clone https://github.com/usernameAI/Dimos

Install RecBole: `pip install recbole`

2. Run Dimos

`python Dimos_run.py`

# Citation

If you find this repository helpful for your work, please cite the following paper:

```bibtex

@article{LI2026114131,
title = {Dimos: Diffusion model with unified sequential state space for session-based recommendation},
journal = {Engineering Applications of Artificial Intelligence},
volume = {169},
pages = {114131},
year = {2026},
issn = {0952-1976},
doi = {https://doi.org/10.1016/j.engappai.2026.114131},
url = {https://www.sciencedirect.com/science/article/pii/S0952197626004124},
author = {Weiyue Li and Ming Gao and Bowei Chen and Jingmin An and Hao Dong and Wei Jiang and Jiafu Tang},
}
