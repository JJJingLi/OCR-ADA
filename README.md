# Towards Better Long-Tailed Oracle Character Recognition with Adversarial Data Augmentation (PR2023)

PyTorch official implementation of "[Towards Better Long-Tailed Oracle Character Recognition with Adversarial Data Augmentation (PR2023)](https://doi.org/10.1016/j.patcog.2023.109534)", *Jing Li*, *Qiu-Feng Wang*, *Kaizhu Huang*, *Xi Yang*, *Rui Zhang*, *John Y. Goulermas*.

> **Abstract:** *Deciphering oracle bone script is of great significance to the study of ancient Chinese culture as well as archaeology.
Although recent studies on oracle character recognition have made substantial progress, they still suffer from the long-tailed data situation that results in a noticeable performance drop on the tail classes. To mitigate this issue, we propose a generative adversarial framework to augment oracle characters in the problematic classes. In this framework, the generator produces synthetic data through convex combinations of all the available samples in the corresponding classes, and is further optimized through adversarial learning with the classifier and simultaneously the discriminator. Meanwhile, we introduce Repatch to generalize samples in the generator. Since tail classes do not have sufficient data for convex combinations, we propose the TailMix mechanism to generate suitable tail class samples from other classes. Experimental results show that our proposed algorithm obtains remarkable performance in oracle character recognition and achieves new state-of-the-art average (total) accuracy with 86.03\% (89.46\%), 86.54\% (93.86\%), 95.22\% (96.17\%) on the three datasets Oracle-AYNU, OBC306 and Oracle-20K, respectively.*


## Data
[Oracle-20K](https://doi.org/10.1109/TIP.2015.2500019), [Oracle-AYNU](https://doi.org/10.1109/ICDAR.2019.00057) and [OBC306](https://doi.org/10.1109/ICDAR.2019.00114) are provided by other institutions and are not publicly accessible at current. We do not have the right to distribute these datasets. Researchers interested in accessing these datasets should contact the respective institutions for more information.


## Requirements
Soon.

## Training and Test
Soon.

## Citation

If you use our code or paper, please cite our paper:
```
@article{li2023towards,
  author       = {Jing Li, Qiu{-}Feng Wang, Kaizhu Huang, Xi Yang, Rui Zhang and John Yannis Goulermas},
  title        = {Towards better long-tailed oracle character recognition with adversarial data augmentation},
  journal      = {Pattern Recognition},
  volume       = {140},
  pages        = {109534},
  year         = {2023}
}
```

## Acknowledgments
Our code is developed based on [GAMO](https://github.com/SankhaSubhra/GAMO) and [PatchUp](https://github.com/chandar-lab/PatchUp). Thank them for sharing.
