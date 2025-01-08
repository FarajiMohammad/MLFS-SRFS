# MLFS-SRFS
# 2025-Fusion-Enhanced Multi-Label Feature Selection with Sparse Supplementatio

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
