#### LRSRNet | IEEE TGRS 2025 | HSI-CD
---
## Low-Rank and Sparse Representation Meet Deep Unfolding: A New Interpretable Network for Hyperspectral Change Detection

***Chengle Zhou, Zhi He, Jian Dong, Yunfei Li, Jinchang Ren, and Antonio Plaza***

*IEEE Transactions on Geoscience and Remote Sensing, vol. 63, pp. 1-16, May 2025*

---

![framework](https://github.com/chengle-zhou/MY-IMAGE/blob/3bd29d7ea6331ad4f5e5043aad33e664991ec021/LRSRNet/LRSRNet.jpg)

Fig. 1. Overview of the proposed LRSRNet method.



## Abstract

Hyperspectral image change detection (HSI-CD) is a technique that intelligently checks the changed details in bi-temporal hyperspectral images (Bi-HSIs). Deep learning (DL), with the ability to model nonlinear changing features, has achieved promising results in HSI-CD, but the feature mining mechanism is unclear and the architecture design lacks transparency in such DL models. To alleviate this problem, this paper proposes a new low-rank and sparse representation-based deep unfolding network (LRSRNet) for HSI-CD. For feature mining mechanism, the LRSRNet adopts a low-rank and sparse sub-network (LRSnet) and a change detection sub-network (CDnet). The former is responsible for extracting low-rank features with valuable information and suppressing sparse features containing interference information, while the latter aims to obtain change information from low-rank features. For architecture design, the LRSnet formulates the HSI as a low-rank estimation, sparse estimation, and hyperspectral reconstruction in a low-rank and sparse model, and iteratively optimizes and updates the above sub-problems through deep networks. A new CDnet is designed as a concise convolutional architecture to extract change information from representative Bi-HSIs features. Experiments on three real datasets demonstrate the performance superiority of the proposed LRSRNet method over nine model-driven, data-driven, and model-data-joint-driven HSI-CD algorithms in both qualitative and quantitative evaluations.


## Results

False color images and GT for all datasets. (a)-(c) are false color images of T1 and T2 and GT on the River dataset. (d)-(f) are false color images of T1 and T2 and GT on the Farmland dataset. (g)-(i) are false color images of T1 and T2 and GT on the Santa Barbara dataset. (j) Pixel legend.

![image-1](https://github.com/chengle-zhou/MY-IMAGE/blob/3a8804efe13f6ad114f6f00c6c540f40e5cde5c2/LRSRNet/img-1.jpg)

CD results of various methods on the River dataset. (a) Groundtruth (GT). (b) CVA. (c) PCAKM. (d) IR-MAD. (e) SVM. (f) CSANet. (g) MSDFFN. (h) ReCNN. (i) MSCSCNet. (j) LRSRNet. Note that {\color{red}$\blacksquare$} indicates FP (i.e., over-detection) and {\color{green}$\blacksquare$} represents FN (i.e., under-detection).

![image-2](https://github.com/chengle-zhou/MY-IMAGE/blob/3a8804efe13f6ad114f6f00c6c540f40e5cde5c2/LRSRNet/img-2.jpg)

CD results of various methods on the Farmland dataset. (a) Groundtruth (GT). (b) CVA. (c) PCAKM. (d) IR-MAD. (e) SVM. (f) CSANet. (g) MSDFFN. (h) ReCNN. (i) MSCSCNet. (j) LRSRNet. Note that {\color{red}$\blacksquare$} indicates FP (i.e., over-detection) and {\color{green}$\blacksquare$} represents FN (i.e., under-detection).

![image-3](https://github.com/chengle-zhou/MY-IMAGE/blob/3a8804efe13f6ad114f6f00c6c540f40e5cde5c2/LRSRNet/img-3.jpg)

CD results of various methods on the Santa Barbara dataset. (a) Groundtruth (GT). (b) CVA. (c) PCAKM. (d) IR-MAD. (e) SVM. (f) CSANet. (g) MSDFFN. (h) ReCNN. (i) MSCSCNet. (j) LRSRNet. Note that {\color{red}$\blacksquare$} indicates FP (i.e., over-detection) and {\color{green}$\blacksquare$} represents FN (i.e., under-detection).

![image-4](https://github.com/chengle-zhou/MY-IMAGE/blob/3a8804efe13f6ad114f6f00c6c540f40e5cde5c2/LRSRNet/img-4.jpg)



In preparation for release soon.

Please cite our new paper:

**Plain Text:**

Chengle Zhou, Zhi He, Jian Dong, Yunfei Li, Jinchang Ren and Antonio Plaza, "[Low-Rank and Sparse Representation Meet Deep Unfolding: A New Interpretable Network for Hyperspectral Change Detection](https://ieeexplore.ieee.org/document/11002607)," ***IEEE Transactions on Geoscience and Remote Sensing***, vol. 63, pp. 1-16, 2025, Art no. 5513516, doi: 10.1109/TGRS.2025.

**BibTex:**

```latex
@ARTICLE{zhou2025lrsrnet,
  author={Zhou, Chengle and He, Zhi and Dong, Jian and Li, Yunfei and Ren, Jinchang and Plaza, Antonio},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Low-Rank and Sparse Representation Meet Deep Unfolding: A New Interpretable Network for Hyperspectral Change Detection}, 
  year={2025},
  volume={63},
  number={},
  pages={1-16},
  keywords={Feature extraction;Hyperspectral imaging;Sparse matrices;Sparse approximation;Noise;Iterative methods;Optimization;Transformers;Principal component analysis;Estimation;Bitemporal hyperspectral images (Bi-HSIs);change detection;deep unfolding;low-rank and sparse representation},
  doi={10.1109/TGRS.2025.3564996}}
```




