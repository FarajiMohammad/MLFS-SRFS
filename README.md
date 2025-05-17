# [Fusion-Enhanced Multi-Label Feature Selection with Sparse Supplementatio (2025)](https://www.sciencedirect.com/science/article/abs/pii/S1566253524005918)

The exponential increase of multi-label data over various domains demands the development of effective
feature selection methods. However, current sparse-learning-based feature selection methods that use LASSOnorm
and 𝑙2,1-norm fail to handle two crucial issues for multi-label data. Firstly, LASSO-based methods remove
features with zero-weight values during the feature selection process, some of which may have a certain
degree of classification ability. Secondly, 𝑙2,1-norm-based methods may select redundant features that lead to
inefficient classification results. To overcome these issues, we propose a novel sparse supplementation norm
that combines inner product regularization and 𝑙2,1-norm as a novel fusion norm. This innovative fusion norm
is designed to enhance the sparsity of feature selection models by leveraging the inherent row-sparse property
in the 𝑙2,1-norm. Specifically, the inner product regularization norm can maintain features with potentially
useful classification information, which may be discarded in traditional LASSO-based methods. At the same
time, the inner product regularization norm can remove redundant features, which is introduced in traditional
𝑙2,1-norm-based methods. By incorporating this fusion norm into the Sparse-supplementation Regularized multilabel
Feature Selection (SRFS) model, our method mitigates feature omission and feature redundancy, ensuring
more effective and efficient feature selection for multi-label classification tasks. The experimental results on
various benchmark datasets validate the efficiency and effectiveness of our proposed SRFS model.

If you find this implementation helpful in your work, please consider citing both the original paper and our related research on multi-label feature selection:

## Original Paper:

```
@article{li2025fusion,
  title={Fusion-enhanced multi-label feature selection with sparse supplementation},
  author={Li, Yonghao and Wang, Xiangkun and Yang, Xin and Gao, Wanfu and Ding, Weiping and Li, Tianrui},
  journal={Information Fusion},
  volume={117},
  pages={102813},
  year={2025},
  publisher={Elsevier}
}
```
## Our Paper:
```
@article{faraji2024multi,
  title={Multi-label feature selection with global and local label correlation},
  author={Faraji, Mohammad and Seyedi, Seyed Amjad and Tab, Fardin Akhlaghian and Mahmoodi, Reza},
  journal={Expert Systems with Applications},
  volume={246},
  pages={123198},
  year={2024},
  publisher={Elsevier}
}
```
