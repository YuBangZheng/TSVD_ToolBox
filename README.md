# Transformed T-SVD Toolbox (Matlab)

Yu-Bang Zheng, Xi-Le Zhao, Qibin Zhao, Junjun Pan, Michael K. Ng, Heng-Chao Li, Ting-Zhu Huang


<p align="center">
    <br>
    <img src="transtsvd.png" width="100%"/>
    <br>
</p>

## 1. Introduction

The transformed tensor singular values decomposition (t-SVD) captures the low-rankness of the frontal slices under the given transform, which mitigates the inherent information loss to matricization or tensor flattening. We develop a TranTSVD toolbox in Matlab with the tensor completion task as an example. The TranTSVD toolbox includes the classical transformed t-SVD methods [1], such as the standrad DFT-based TNN [2,3,4], the unitary transformed TNN (UTNN) [5], the framelet transformed TNN (FTNN) [6], and the nonlinear transformed TNN (NTTNN) [7].

## 2. Example

Simply run the “Demo.m” to test all the transformed t-SVD methods. The test data is available at http://trace.eas.asu.edu/yuv/.

## 3. Citation

Please cite the corresponding references when using the TenNet toolbox in your papers.

[1] T.-X. Jiang, M. K. Ng, and X.-L. Zhao, “Chapter 2: Transform-based tensor singular value decomposition in multidimensional image recovery,” in Tensors for Data Processing, Y. Liu, Ed. Academic Press, 2022, pp. 31–60.

[2] M. E. Kilmer and C. D. Martin, “Factorization strategies for third-order tensors,” Linear Algebra and its Applications, vol. 435, no. 3, pp. 641–658, 2011.

[3] Z. Zhang and S. Aeron, “Exact tensor completion using t-SVD,” IEEE Transactions on Signal Processing, vol. 65, no. 6, pp. 1511-1526, 2017.

[4] C. Lu, J. Feng, Y. Chen, W. Liu, Z. Lin, and S. Yan, “Tensor robust principal component analysis with a new tensor nuclear norm,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 42, no. 4, pp. 925–938, 2020.

[5] G.-J. Song, M. K. Ng, and X.-J. Zhang, “Robust tensor completion using transformed tensor singular value decomposition,” Numerical Linear Algebra with Applications, vol. 27, p. e2299, 2020.

[6] T.-X. Jiang, M. K. Ng, X.-L. Zhao, and T.-Z. Huang, “Framelet representation of tensor nuclear norm for third-order tensor completion,” IEEE Transactions on
Image Processing, vol. 29, pp. 7233–7244, 2020.

[7] B.-Z. Li, X.-L. Zhao, T.-Y. Ji, X.-J. Zhang, and T.-Z. Huang, “Nonlinear transform induced tensor nuclear norm for tensor completion,” Journal of Scientific
Computing, vol. 92, 2022.

