# Continuous-Representation-Zoo

This project summarizes the papers and studies introduced in the review: Continuous Representation Methods, Theories, and Applications: An Overview and Perspectives 📖

# Abstract ✨

Recently, continuous representation methods emerge as novel paradigms that characterize the intrinsic structures of real-world data through function representations that map positional coordinates to their corresponding values in the continuous space. As compared with the traditional discrete framework, the continuous framework demonstrates inherent superiority for data representation and reconstruction (e.g., image restoration, novel view synthesis, and waveform inversion) by offering inherent advantages including resolution flexibility, cross-modal adaptability, inherent smoothness, and parameter efficiency. In this review, we systematically examine recent advancements in continuous representation frameworks, focusing on three aspects: (i) Continuous representation method designs such as basis function representation, statistical modeling, tensor function decomposition, and implicit neural representation; (ii) Theoretical foundations of continuous representations such as approximation error analysis, convergence property, and implicit regularization; (iii) Real-world applications of continuous representations derived from computer vision, graphics, bioinformatics, and remote sensing. Furthermore, we outline future directions and perspectives to inspire exploration and deepen insights to facilitate continuous representation methods, theories, and applications.

<p align="center">
    <img src="imgs/diagram.png" width="100%">
</p>

    bibtex:
    @article{arXiv2025Luo,
     author  = {Yisi Luo, Xile Zhao, Deyu Meng},
     title   = {Continuous Representation Methods, Theories, and Applications: An Overview and Perspectives},
     journal = {arXiv:},
     year    = {2025},
    }


# Continuous Methods (Parametric model)

<p align="center">
    <img src="imgs/method1.png" width="100%">
</p>

## Basis Function Representation

- Tatsuya Yokota, Rafal Zdunek, Andrzej Cichocki, and Yukihiko Yamashita. Smooth nonnegative matrix and tensor factorizations for robust multi-way data analysis. Signal Processing, 2015. 

- Otto Debals, Marc Van Barel, and Lieven De Lathauwer. Nonnegative matrix factorization using nonnegative polynomial approximations. IEEE Signal Processing Letters, 2017 

- Masaaki Imaizumi and Kohei Hayashi. Tensor decomposition with smoothness. In International Conference on Machine
Learning, 2017. 

- Alex A. Gorodetsky and John D. Jakeman. Gradient-based optimization for regression in the functional tensor-train format.
Journal of Computational Physics, 2018.

- Nikos Kargas and Nicholas D. Sidiropoulos. Nonlinear system identification via tensor completion. In Proceedings of the
AAAI Conference on Artificial Intelligence, 2020. 

- Nikos Kargas and Nicholas D. Sidiropoulos. Supervised learning and canonical decomposition of multivariate functions. IEEE Transactions on Signal Processing, 2021. 

- Lucas Sort, Laurent Le Brusquet, and Arthur Tenenhaus. Latent functional parafac for modeling multidimensional longitudinal
data. arXiv, 2410.18696, 2024. 

- Peter Kunkel and Volker Mehrmann. Smooth factorizations of matrix-valued functions and their derivatives. Numerische Mathematik, 1991.

- I. V. Oseledets. Constructive representation of functions in low-rank tensor formats. Constructive Approximation, 2013.
  
- Petr Tichavsky and Ondrej Straka. Tensor train approximation of multivariate functions. In 2024 32nd European Signal
Processing Conference, 2024. 

- Tianqi Chen, Hang Li, Qiang Yang, and Yong Yu. General functional matrix factorization using gradient boosting. In Proceedings of the 30th International Conference on International Conference on Machine Learning, 2013. 

- Behnam Hashemi and Lloyd N. Trefethen. Chebfun in three dimensions. SIAM Journal on Scientific Computing, 2017. 

- Ziming Liu, Yixuan Wang, Sachin Vaidya, Fabian Ruehle, James Halverson, Marin Soljacic, Thomas Y. Hou, and Max Tegmark. KAN: Kolmogorov-Arnold networks. In The Thirteenth International Conference on Learning Representations, 2025. 

- Tongle Wu and Jicong Fan. Smooth tensor product for tensor completion. IEEE Transactions on Image Processing, 2024. 

## Implicit Neural Representation

- Matthew Tancik, Pratul Srinivasan, Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, Ravi Ramamoorthi, Jonathan Barron, and Ren Ng. Fourier features let networks learn high-frequency functions in low-dimensional domains. In International Conference on Neural Information Processing Systems, 2020.

- Vincent Sitzmann, Julien Martel, Alexander Bergman, David Lindell, and Gordon Wetzstein. Implicit neural representations
with periodic activation functions. In International Conference on Neural Information Processing Systems, 2020.

- Rizal Fathony, Anit Kumar Sahu, Devin Willmott, and J Zico Kolter. Multiplicative filter networks. In International
Conference on Learning Representations, 2021.

- Vishwanath Saragadam, Daniel LeJeune, Jasper Tan, Guha Balakrishnan, Ashok Veeraraghavan, and Richard G. Baraniuk.
Wire: Wavelet implicit neural representations. In 2023 IEEE/CVF Conference on Computer Vision and Pattern
Recognition, 2023.

- Jason Chun Lok Li, Chang Liu, Binxiao Huang, and Ngai Wong. Learning spatially collaged fourier bases for implicit neural
representation. In Proceedings of the AAAI Conference on Artificial Intelligence, 2024.

- Zhen Liu, Hao Zhu, Qi Zhang, Jingde Fu, Weibing Deng, Zhan Ma, Yanwen Guo, and Xun Cao. Finer: Flexible spectral bias
tuning in implicit neural representation by variable-periodic activation functions. In 2024 IEEE/CVF Conference on
Computer Vision and Pattern Recognition, 2024.

- Dhananjaya Jayasundara, Heng Zhao, Demetrio Labate, and Vishal M. Patel. PIN: Prolate spheroidal wave function-based
implicit neural representations. In The Thirteenth International Conference on Learning Representations, 2025.

- Sameera Ramasinghe and Simon Lucey. Beyond periodicity: Towards a unifying framework for activations in coordinatemlps.
In 17th European Conference on Computer Vision, 2022.

- Kexuan Shi, Xingyu Zhou, and Shuhang Gu. Improved implicit neural representation with Fourier reparameterized training.
In 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2024.

- Zekun Hao, Arun Mallya, Serge Belongie, and Ming-Yu Liu. Implicit neural representations with levels-of-experts. In
Advances in Neural Information Processing Systems, 2022.

- Yizhak Ben-Shabat, Chamin Hewa Koneputugodage, Sameera Ramasinghe, and Stephen Gould. Neural experts: Mixture
of experts for implicit neural representations. In Advances in Neural Information Processing Systems, 2024.

- Kushal Vyas, Ahmed Imtiaz Humayun, Aniket Dashpute, Richard Baraniuk, Ashok Veeraraghavan, and Guha Balakrishnan. Learning transferable features for implicit neural representations. In The Thirty-eighth Annual Conference on Neural Information Processing Systems, 2024.

- Chen Zhang, Steven Tin Sui Luo, Jason Chun Lok Li, Yik Chung Wu, and Ngai Wong. Nonparametric teaching of implicit neural representations. In Proceedings of the 41st International Conference on Machine Learning, 2024.

- Wei Fang, Yuxing Tang, Heng Guo, Mingze Yuan, Tony C.W. Mok, Ke Yan, Jiawen Yao, Xin Chen, Zaiyi Liu, Le Lu, Ling Zhang, and Minfeng Xu. Cycleinr: Cycle implicit neural representation for arbitrary-scale volumetric super-resolution of medical data. In 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2024.

- Vishwanath Saragadam, Jasper Tan, Guha Balakrishnan, Richard G. Baraniuk, and Ashok Veeraraghavan. Miner: Multiscale implicit neural representation. In 17th European Conference on Computer Vision, 2022.

- Jiayi Li, Xile Zhao, Jianli Wang, Chao Wang, and Min Wang. Superpixel-informed implicit neural representation for multi-dimensional data. In 18th European Conference on Computer Vision, 2024.

- Zhicheng Cai, Hao Zhu, Qiu Shen, Xinran Wang, and Xun Cao. Batch normalization alleviates the spectral bias in coordinate networks. In 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2024.

- Chang Yu, Yisi Luo, Kai Ye, Xile Zhao, and Deyu Meng. Cross-frequency implicit neural representation with self-evolving
parameters. arXiv:2504.10929, 2025.

- Amirhossein Kazerouni, Reza Azad, Alireza Hosseini, Dorit Merhof, and Ulas Bagci. Incode: Implicit neural conditioning
with prior knowledge embeddings. In 2024 IEEE/CVF Winter Conference on Applications of Computer Vision, 2024.

- Yinbo Chen and Xiaolong Wang. Transformers as meta-learners for implicit neural representations. In European Conference
on Computer Vision, 2022.

- Matthew Tancik, Ben Mildenhall, Terrance Wang, Divi Schmidt, Pratul P. Srinivasan, Jonathan T. Barron, and Ren Ng.
Learned initializations for optimizing coordinate-based neural representations. In Proceedings of the IEEE/CVF Conference
on Computer Vision and Pattern Recognition, 2021.

- Gizem Yuce, Guillermo Ortiz-Jimenez, Beril Besbinar, and Pascal Frossard. A structured dictionary perspective on implicit
neural representations. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2022.

## Grid Encoding Parametric Model

- Thomas Muller, Alex Evans, Christoph Schied, and Alexander Keller. Instant neural graphics primitives with a multiresolution
hash encoding. ACM Transactions on Graphics, 2022.

- Anpei Chen, Zexiang Xu, Andreas Geiger, Jingyi Yu, and Hao Su. Tensorf: Tensorial radiance fields. In 17th European Conference on Computer Vision, 2022.

- Cheng Sun, Min Sun, and Hwann-Tzong Chen. Direct voxel grid optimization: Super-fast convergence for radiance fields
reconstruction. In 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2022.

- Alex Yu, Ruilong Li, Matthew Tancik, Hao Li, Ren Ng, and Angjoo Kanazawa. Plenoctrees for real-time rendering of neural
radiance fields. In 2021 IEEE/CVF International Conference on Computer Vision, 2021.

- Sara Fridovich-Keil, Alex Yu, Matthew Tancik, Qinhong Chen, Benjamin Recht, and Angjoo Kanazawa. Plenoxels: Radiance fields without neural networks. In 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2022.

- Hao Zhu, Shaowen Xie, Zhen Liu, Fengyi Liu, Qi Zhang, You Zhou, Yi Lin, Zhan Ma, and Xun Cao. Disorder-invariant
implicit neural representation. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2024.

- Hao Zhu, Fengyi Liu, Qi Zhang, Zhan Ma, and Xun Cao. RHINO: Regularizing the hash-based implicit neural representation. Science China Information Sciences, 2025.

# Continuous Methods (Structural modeling)

<p align="center">
    <img src="imgs/method2.png" width="100%">
</p>

# Theoretical Foundations

<p align="center">
    <img src="imgs/theory.png" width="100%">
</p>

# Applications

<p align="center">
    <img src="imgs/application.png" width="100%">
</p>


