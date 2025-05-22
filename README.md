# Continuous-Representation-Zoo

This project summarizes the papers and studies introduced in the review: Continuous Representation Methods, Theories, and Applications: An Overview and Perspectives [<a href="http://export.arxiv.org/abs/2505.15222">arXiv</a>] 📖

# Abstract ✨

Recently, continuous representation methods emerge as novel paradigms that characterize the intrinsic structures of real-world data through function representations that map positional coordinates to their corresponding values in the continuous space. As compared with the traditional discrete framework, the continuous framework demonstrates inherent superiority for data representation and reconstruction (e.g., image restoration, novel view synthesis, and waveform inversion) by offering inherent advantages including resolution flexibility, cross-modal adaptability, inherent smoothness, and parameter efficiency. In this review, we systematically examine recent advancements in continuous representation frameworks, focusing on three aspects: (i) Continuous representation method designs such as basis function representation, statistical modeling, tensor function decomposition, and implicit neural representation; (ii) Theoretical foundations of continuous representations such as approximation error analysis, convergence property, and implicit regularization; (iii) Real-world applications of continuous representations derived from computer vision, graphics, bioinformatics, and remote sensing. Furthermore, we outline future directions and perspectives to inspire exploration and deepen insights to facilitate continuous representation methods, theories, and applications.

<p align="center">
    <img src="imgs/diagram.png" width="100%">
</p>

    bibtex:
    @article{arXiv2025Luo,
     author  = {Yisi Luo, Xile Zhao, Deyu Meng},
     title   = {Continuous Representation Methods, Theories, and Applications: An Overview and Perspectives},
     journal = {arXiv:2505.15222},
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

## Matrix and Tensor Function Decomposition

- Ruofan Liang, Hongyi Sun, and Nandita Vijaykumar. CoordX: Accelerating implicit neural representation with a split MLP architecture. In International Conference on Learning Representations, 2022.

- Yisi Luo, Xile Zhao, Zhemin Li, Michael K. Ng, and Deyu Meng. Low-rank tensor function representation for multidimensional data recovery. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2024.

- Jianli Wang and Xile Zhao. Functional transform-based low-rank tensor factorization for multi-dimensional data recovery. In 18th European Conference on Computer Vision, 2024.

- Yanyi Li, Xi Zhang, Yisi Luo, and Deyu Meng. Deep rank-one tensor functional factorization for multi-dimensional data recovery. In Proceedings of the AAAI Conference on Artificial Intelligence, 2025.

- Sai Karthikeya Vemuri, Tim Buchner, and Joachim Denzler. F-INR: Functional tensor decomposition for implicit neural representations. arXiv:2503.21507, 2025.

- Tong Nie, Guoyang Qin, Wei Ma, and Jian Sun. Spatiotemporal implicit neural representation as a generalized traffic data learner. Transportation Research Part C: Emerging Technologies, 2024.

## Statistical and Bayesian Framework

- Shikai Fang, Qingsong Wen, Yingtao Luo, Shandian Zhe, and Liang Sun. BayOTIDE: Bayesian online multivariate time series imputation with functional decomposition. In Proceedings of the 41st International Conference on Machine Learning, 2024.

- Shikai Fang, Xin Yu, Shibo Li, Zheng Wang, Robert M. Kirby, and Shandian Zhe. Streaming factor trajectory learning for temporal tensor decomposition. In Proceedings of the 37th International Conference on Neural Information Processing
Systems, 2023.

- Shikai Fang, Xin Yu, Zheng Wang, Shibo Li, Mike Kirby, and Shandian Zhe. Functional Bayesian Tucker decomposition for continuous-indexed tensor data. In The Twelfth International Conference on Learning Representations, 2024.

- Panqi Chen, Lei Cheng, Jianlong Li, Weichang Li, Weiqing Liu, Jiang Bian, and Shikai Fang. Generalized temporal tensor decomposition with rank-revealing latent-ODE. Arxiv: 2502.06164, 2025.

## Continuous Regularization for Structural Modeling

- Jelmer M Wolterink, Jesse C Zwienenberg, and Christoph Brune. Implicit neural representations for deformable image registration. In Proceedings of The 5th International Conference on Medical Imaging with Deep Learning, 2022.

- Zhemin Li, Hongxia Wang, and Deyu Meng. Regularize implicit neural representation by itself. In 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2023.

- Yisi Luo, Xile Zhao, and Deyu Meng. Revisiting nonlocal self-similarity from continuous representation. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2025.

- Yisi Luo, Xile Zhao, Kai Ye, and Deyu Meng. Neurtv: Total variation on the neural domain. SIAM Journal on Imaging Sciences, 2025.

- Hyeongjun Heo, Seonghun Oh, Jae Yong Lee, Young Min Kim, and Yonghyeon Lee. Isometric regularization for manifolds of functional data. In The Thirteenth International Conference on Learning Representations, 2025.

# Theoretical Foundations

<p align="center">
    <img src="imgs/theory.png" width="100%">
</p>

## Approximation and Representation Theory

- Alex Gorodetsky, Sertac Karaman, and Youssef Marzouk. A continuous analogue of the tensor-train decomposition. Computer Methods in Applied Mechanics and Engineering, 2019.

- Michael Griebel and Guanglian Li. On the decay rate of the singular values of bivariate functions. SIAM Journal on Numerical Analysis, 2018.

- Rungang Han, Pixu Shi, and Anru R. Zhang and. Guaranteed functional tensor singular value decomposition. Journal of the American Statistical Association, 2024.

- Behnam Hashemi and Lloyd N. Trefethen. Chebfun in three dimensions. SIAM Journal on Scientific Computing, 2017.

- S.W. Ellacott. Aspects of the numerical analysis of neural networks. Acta Numerica, 1994.

- Kurt Hornik, Maxwell Stinchcombe, and Halbert White. Multilayer feedforward networks are universal approximators. Neural Networks, 1989.

- Gerlind Plonka, Daniel Potts, Gabriele Steidl, and Manfred Tasche. Numerical Fourier Analysis, chapter 7, pages 235–259. John Wiley & Sons, Ltd, 2020.

- Gizem Yu ̈ce, Guillermo Ortiz-Jim ́enez, Beril Besbinar, and Pascal Frossard. A structured dictionary perspective on implicit neural representations. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2022.

- T Mitchell Roddenberry, Vishwanath Saragadam, Maarten V. de Hoop, and Richard Baraniuk. Implicit neural representations and the algebra of complex wavelets. In The Twelfth International Conference on Learning Representations, 2024

- Tamara G. Kolda and Brett W. Bader. Tensor decompositions and applications. SIAM Review, 2009

- Michael Griebel and Guanglian Li. On the decay rate of the singular values of bivariate functions. SIAM Journal on Numerical Analysis, 2018.

- Ruofan Liang, Hongyi Sun, and Nandita Vijaykumar. CoordX: Accelerating implicit neural representation with a split MLP architecture. In International Conference on Learning Representations, 2022.

- Yisi Luo, Xile Zhao, Zhemin Li, Michael K. Ng, and Deyu Meng. Low-rank tensor function representation for multi-dimensional data recovery. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2024.

- Andong Wang, Yuning Qiu, Mingyuan Bai, Zhong Jin, Guoxu Zhou, and Qibin Zhao. Generalized tensor decomposition for understanding multi-output regression under combinatorial shifts. In Advances in Neural Information Processing Systems, 2024.

- Rungang Han, Pixu Shi, and Anru R. Zhang and. Guaranteed functional tensor singular value decomposition. Journal of the American Statistical Association, 2024.

- Alex A. Gorodetsky and John D. Jakeman. Gradient-based optimization for regression in the functional tensor-train format. Journal of Computational Physics, 2018.

- Julien Fageot. Variational seasonal-trend decomposition with sparse continuous-domain regularization. arXiv:2505.10486, 2025.

- Sourav Pal, Harshavardhan Adepu, Clinton Wang, Polina Golland, and Vikas Singh. Implicit representations via operator learning. In Forty-first International Conference on Machine Learning, 2024.

- Dejia Xu, Peihao Wang, Yifan Jiang, Zhiwen Fan, and Zhangyang Wang. Signal processing for implicit neural representations. In Advances in Neural Information Processing Systems, 2022.



## Generalization and Convergence

- Kexuan Shi, Xingyu Zhou, and Shuhang Gu. Improved implicit neural representation with fourier reparameterized training. In 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2024.

- Matthew Tancik, Pratul Srinivasan, Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, Ravi Ramamoorthi, Jonathan Barron, and Ren Ng. Fourier features let networks learn high frequency functions in low dimensional
domains. In International Conference on Neural Information Processing Systems, 2020.

- Arthur Jacot, Franck Gabriel, and Cl´ement Hongler. Neural tangent kernel: convergence and generalization in neural networks. In Proceedings of the 32nd International Conference on Neural Information Processing Systems, 2018.

- Sanjeev Arora, Simon Du, Wei Hu, Zhiyuan Li, and Ruosong Wang. Fine-grained analysis of optimization and generalization for overparameterized two-layer neural networks. In Proceedings of the 36th International Conference on Machine Learning, 2019.

- Zhen Liu, Hao Zhu, Qi Zhang, Jingde Fu, Weibing Deng, Zhan Ma, Yanwen Guo, and Xun Cao. Finer: Flexible spectral-bias tuning in implicit neural representation by variableperiodic activation functions. In 2024 IEEE/CVF Conference on
Computer Vision and Pattern Recognition, 2024.

- Vincent Sitzmann, Julien Martel, Alexander Bergman, David Lindell, and Gordon Wetzstein. Implicit neural representations with periodic activation functions. In International Conference on Neural Information Processing Systems, 2020.

- Dhananjaya Jayasundara, Heng Zhao, Demetrio Labate, and Vishal M. Patel. PIN: Prolate spheroidal wave function-based implicit neural representations. In The Thirteenth International Conference on Learning Representations, 2025.

- Sanjeev Arora, Simon S. Du, Wei Hu, Zhiyuan Li, Ruslan Salakhutdinov, and Ruosong Wang. On exact computation with an infinitely wide neural net. In Proceedings of the 33rd International Conference on Neural Information Processing
Systems, 2019.

- Colin Wei, Jason D. Lee, Qiang Liu, and Tengyu Ma. Regularization matters: generalization and optimization of neural nets v.s. their induced kernel. In Proceedings of the 33rd International Conference on Neural Information Processing Systems, 2019.

- Zonghao Chen, Xupeng Shi, Tim G. J. Rudner, Qixuan Feng, Weizhong Zhang, and Tong Zhang. A neural tangent kernel perspective on function-space regularization in neural networks. In International Conference on Neural Information
Processing Systems Workshop on Optimization for Machine Learning, 2022.

- Zixiang Chen, Yuan Cao, Quanquan Gu, and Tong Zhang. A generalized neural tangent kernel analysis for two-layer neural networks. In Proceedings of the 34th International Conference on Neural Information Processing Systems, 2020.

- Amnon Geifman, Daniel Barzilai, Ronen Basri, and Meirav Galun. Controlling the inductive bias of wide neural networks by modifying the kernel’s spectrum. Transactions on Machine Learning Research, 2024.

- Shin-Fang Chng, Hemanth Saratchandran, and Simon Lucey. Preconditioners for the stochastic training of neural fields. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2025.

- Ismail Alkhouri, Evan Bell, Avrajit Ghosh, Shijun Liang, Rongrong Wang, and Saiprasad Ravishankar. Understanding untrained deep models for inverse problems: Algorithms and theory. Arxiv: 2502.18612, 2025.

- Samuel Audia, Soheil Feizi, Matthias Zwicker, and Dinesh Manocha. How learnable grids recover fine detail in low dimensions: A neural tangent kernel analysis of multigrid parametric encodings. In The Thirteenth International Conference on
Learning Representations, 2025.

- Zhen Liu, Hao Zhu, Qi Zhang, Jingde Fu, Weibing Deng, Zhan Ma, Yanwen Guo, and Xun Cao. Finer: Flexible spectral-bias tuning in implicit neural representation by variableperiodic activation functions. In 2024 IEEE/CVF Conference on
Computer Vision and Pattern Recognition, 2024.

- Andrea Bonfanti, Giuseppe Bruno, and Cristina Cipriani. The challenges of the nonlinear regime for physics-informed neural networks. In Advances in Neural Information Processing Systems, 2024.

- Mike Nguyen and Nicole M¨ucke. Optimal convergence rates for neural operators. ArXiv:2412.17518, 2025.


## Implicit Regularization

- Sanjeev Arora, Nadav Cohen, Wei Hu, and Yuping Luo. Implicit regularization in deep matrix factorization. In Proceedings
of the 33rd International Conference on Neural Information Processing Systems, 2019.

- Noam Razin, Asaf Maman, and Nadav Cohen. Implicit regularization in hierarchical tensor factorization and deep convolu-
tional neural networks. In Proceedings of the 39th International Conference on Machine Learning, 2022.

- Suriya Gunasekar, Blake E Woodworth, Srinadh Bhojanapalli, Behnam Neyshabur, and Nati Srebro. Implicit regularization in matrix factorization. In Advances in Neural Information Processing Systems, 2017.

- Noam Razin, Asaf Maman, and Nadav Cohen. Implicit regularization in hierarchical tensor factorization and deep convolutional neural networks. In Proceedings of the 39th International Conference on Machine Learning, 2022.

- Kais Hariz, Hachem Kadri, Stephane Ayache, Maher Moakher, and Thierry Artieres. Implicit regularization with polynomial growth in deep tensor factorization. In Proceedings of the 39th International Conference on Machine Learning, 2022.

- Kais Hariz, Hachem Kadri, St´ephane Ayache, Maher Moakher, and Thierry Arti`eres. Implicit regularization in deep tucker factorization: Low-rankness via structured sparsity. In International Conference on Artificial Intelligence and Statistics, 2024.

- Zhiwei Bai, Jiajie Zhao, and Yaoyu Zhang. Connectivity shapes implicit regularization in matrix factorization models for matrix completion. In The Thirty-eighth Annual Conference on Neural Information Processing Systems, 2024.

- Shuo Xie and Zhiyuan Li. Implicit bias of adamw: $\ell^\infty$-norm constrained optimization. In Proceedings of the 41st International Conference on Machine Learning, 2024.

# Applications

<p align="center">
    <img src="imgs/application.png" width="100%">
</p>

## Vision and Graphics

- Alex Yu, Ruilong Li, Matthew Tancik, Hao Li, Ren Ng, and Angjoo Kanazawa. Plenoctrees for real-time rendering of neural radiance fields. In 2021 IEEE/CVF International Conference on Computer Vision, 2021.

- Anpei Chen, Zexiang Xu, Andreas Geiger, Jingyi Yu, and Hao Su. Tensorf: Tensorial radiance fields. In 17th European Conference on Computer Vision, 2022.

- Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, and Ren Ng. NeRF: Representing scenes as neural radiance fields for view synthesis. In European Conference on Computer Vision, 2020.

- Chiyu Jiang, Avneesh Sud, Ameesh Makadia, Jingwei Huang, Matthias Nießner, and Thomas Funkhouser. Local implicit grid representations for 3d scenes. In 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2020.

- Daniele Grattarola and Pierre Vandergheynst. Generalised implicit neural representations. In Proceedings of the 36th International Conference on Neural Information Processing Systems, 2022.

- Hao Chen, Bo He, Hanyu Wang, Yixuan Ren, Ser Nam Lim, and Abhinav Shrivastava. NeRV: Neural representations for videos. In Advances in Neural Information Processing Systems, 2021.

- Hao Yan, Zhihui Ke, Xiaobo Zhou, Tie Qiu, Xidong Shi, and Dadong Jiang. DS-NeRV: Implicit neural video representation with decomposed static and dynamic codes. In 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2024.

- Jeong Joon Park, Peter Florence, Julian Straub, Richard Newcombe, and Steven Lovegrove. Deepsdf: Learning continuous signed distance functions for shape representation. In 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2019.

- Jiaxiang Tang, Xiaokang Chen, Jingbo Wang, and Gang Zeng. Compressible-composable NeRF via rank-residual decomposition. In Advances in Neural Information Processing Systems, 2022.

- Julian Chibane, Thiemo Alldieck, and Gerard Pons-Moll. Implicit functions in feature space for 3d shape reconstruction and completion. In 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2020.

- Kyle Genova, Forrester Cole, Daniel Vlasic, Aaron Sarna, William Freeman, and Thomas Funkhouser. Learning shape templates with structured implicit functions. In 2019 IEEE/CVF International Conference on Computer Vision, 2019.

- Lars Mescheder, Michael Oechsle, Michael Niemeyer, Sebastian Nowozin, and Andreas Geiger. Occupancy networks: Learning 3d reconstruction in function space. In 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2019.

- Lior Yariv, Jiatao Gu, Yoni Kasten, and Yaron Lipman. Volume rendering of neural implicit surfaces. In Advances in Neural Information Processing Systems, 2021.

- Luiz Schirmer, Tiago Novello, Vin ́ıcius da Silva, Guilherme Schardong, Daniel Perazzo, He ́lio Lopes, Nuno Gonc ̧alves, and Luiz Velho. Geometric implicit neural representations for signed distance functions. Computers & Graphics, 2024.

- Matthew Tancik, Pratul Srinivasan, Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, Ravi Ramamoorthi, Jonathan Barron, and Ren Ng. Fourier features let networks learn high frequency functions in low dimensional domains. In International Conference on Neural Information Processing Systems, 2020.

- Michael Niemeyer, Lars Mescheder, Michael Oechsle, and Andreas Geiger. Differentiable volumetric rendering: Learning implicit 3d representations without 3d supervision. In 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2020.

- Mingyuan Yao, Yukang Huo, Yang Ran, Qingbin Tian, Ruifeng Wang, and Haihua Wang. Neural radiance field-based visual rendering: A comprehensive review. arXiv:2404.00714, 2024.

- Sara Fridovich-Keil, Alex Yu, Matthew Tancik, Qinhong Chen, Benjamin Recht, and Angjoo Kanazawa. Plenoxels: Radiance fields without neural networks. In 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2022.

- Sara Fridovich-Keil, Giacomo Meanti, Frederik Rahbæk Warburg, Benjamin Recht, and Angjoo Kanazawa. K-planes: Explicit radiance fields in space, time, and appearance. In 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2023.

- Seonghyeon Nam, Marcus A. Brubaker, and Michael S. Brown. Neural image representations for multi-image fusion and layer separation. In 17th European Conference on Computer Vision, 2022.

- Shengxiang Hu, Huaijiang Sun, Dong Wei, Xiaoning Sun, and Jin Wang. Continuous heatmap regression for pose estimation via implicit neural representation. In The Thirty-eighth Annual Conference on Neural Information Processing Systems, 2024.

- Shuzhou Yang, Moxuan Ding, Yanmin Wu, Zihan Li, and Jian Zhang. Implicit neural representation for cooperative lowlight image enhancement. In 2023 IEEE/CVF International Conference on Computer Vision, 2023.

- Thomas M ̈uller, Alex Evans, Christoph Schied, and Alexander Keller. Instant neural graphics primitives with a multiresolution hash encoding. ACM Transactions on Graphics, 2022.

- Tianjing Zhang, Yuhui Quan, and Hui Ji. Cross-scale self-supervised blind image deblurring via implicit neural representation. In Advances in Neural Information Processing Systems, 2024.

- Vincent Sitzmann, Julien Martel, Alexander Bergman, David Lindell, and Gordon Wetzstein. Implicit neural representations with periodic activation functions. In International Conference on Neural Information Processing Systems, 2020.

- Vincent Sitzmann, Michael Zollh¨ofer, and Gordon Wetzstein. Scene representation networks: continuous 3d-structure-aware neural scene representations. In Proceedings of the 33rd International Conference on Neural Information Processing Systems, 2019.

- Wenbo Zhao, Xianming Liu, Deming Zhai, Junjun Jiang, and Xiangyang Ji. Self-supervised arbitrary-scale implicit point clouds upsampling. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023.

- Xiang Chen, Jinshan Pan, and Jiangxin Dong. Bidirectional multi-scale implicit neural representations for image deraining. In 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2024. 

- Xinyue Xia, Gal Mishne, and Yusu Wang. Implicit graphon neural representation. In Proceedings of The 26th International Conference on Artificial Intelligence and Statistics, 2023.

- Yinbo Chen, Sifei Liu, and Xiaolong Wang. Learning continuous image representation with local implicit image function. In 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2021.

- Zeyuan Chen, Yinbo Chen, Jingwen Liu, Xingqian Xu, Vidit Goel, Zhangyang Wang, Humphrey Shi, and Xiaolong Wang. Videoinr: Learning video implicit neural representation for continuous space-time super-resolution. In 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2022.

- Zhiqin Chen and Hao Zhang. Learning implicit fields for generative shape modeling. In 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2019. 

- Ziheng Cheng, Yucheng Ding, Chunhui Qu, and Bo Chen. Implicit neural representation with imaging geometry for sar target recognition. IEEE Transactions on Aerospace and Electronic Systems, 2025.

- Zizhang Li, Mengmeng Wang, Huaijin Pi, Kechun Xu, Jianbiao Mei, and Yong Liu. E-NeRV: Expedite neural video representation with disentangled spatial-temporal context. In 17th European Conference on Computer Vision, 2022.


## Scientific Computing

- George Em Karniadakis, Ioannis G. Kevrekidis, Lu Lu, Paris Perdikaris, Sifan Wang, and Liu Yang. Physics-informed machine learning. Nature Reviews Physics, 2021.

- M. Raissi, P. Perdikaris, and G.E. Karniadakis. Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations. Journal of Computational Physics, 2019.

- Vincent Sitzmann, Julien Martel, Alexander Bergman, David Lindell, and Gordon Wetzstein. Implicit neural representations with periodic activation functions. In International Conference on Neural Information Processing Systems, 2020.

- Matthew Tancik, Pratul Srinivasan, Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, Ravi Ramamoorthi, Jonathan Barron, and Ren Ng. Fourier features let networks learn high frequency functions in low dimensional domains. In International Conference on Neural Information Processing Systems, 2020.

- Haoteng Hu, Lehua Qi, and Xujiang Chao. Physics-informed neural networks (PINN) for computational solid mechanics: Numerical frameworks and applications. Thin-Walled Structures, 2024.

- George Em Karniadakis, Ioannis G. Kevrekidis, Lu Lu, Paris Perdikaris, Sifan Wang, and Liu Yang. Physics-informed machine learning. Nature Reviews Physics, 2021.

- Chi Zhao, Feifei Zhang, Wenqiang Lou, Xi Wang, and Jianyong Yang. A comprehensive review of advances in physicsinformed neural networks and their applications in complex fluid dynamics. Physics of Fluids, 2024.

- Thomas M ̈uller, Alex Evans, Christoph Schied, and Alexander Keller. Instant neural graphics primitives with a multiresolution hash encoding. ACM Transactions on Graphics, 2022.

- Namgyu Kang, Byeonghyeon Lee, Youngjoon Hong, Seok-Bae Yun, and Eunbyung Park. Pixel: physics-informed cell representations for fast and accurate pde solvers. In Proceedings of the Thirty-Seventh AAAI Conference on Artificial Intelligence, 2023.

- Thomas M ̈uller, Alex Evans, Christoph Schied, and Alexander Keller. Instant neural graphics primitives with a multiresolution hash encoding. ACM Transactions on Graphics, 2022.

- Ge Jin, Deyou Wang, Jian Cheng Wong, and Shipeng Li. Differentiable hash encoding for physics-informed neural networks. In 2024 IEEE Conference on Artificial Intelligence, 2024.

- Haoxiang Wang, Tao Yu, Tianwei Yang, Hui Qiao, and Qionghai Dai. Neural physical simulation with multi-resolution hash grid encoding. Proceedings of the AAAI Conference on Artificial Intelligence, 2024.

- Xinquan Huang and Tariq Alkhalifah. Efficient physics-informed neural networks using hash encoding. Journal of Computational Physics, 2024.

- Namgyu Kang, Jaemin Oh, Youngjoon Hong, and Eunbyung Park. PIG: Physics-informed gaussians as adaptive parametric mesh representations. In The Thirteenth International Conference on Learning Representations, 2025.

- Lu Lu, Pengzhan Jin, Guofei Pang, Zhongqiang Zhang, and George Em Karniadakis. Learning nonlinear operators via DeepONet based on the universal approximation theorem of operators. Nature Machine Intelligence, 2021.

- Nikola Kovachki, Zongyi Li, Burigede Liu, Kamyar Azizzadenesheli, Kaushik Bhattacharya, Andrew Stuart, and Anima Anandkumar. Neural operator: learning maps between function spaces with applications to pdes. Journal of Machine Learning Research, 2023.

- Zongyi Li, Nikola Borislavov Kovachki, Kamyar Azizzadenesheli, Burigede liu, Kaushik Bhattacharya, Andrew Stuart, and Anima Anandkumar. Fourier neural operator for parametric partial differential equations. In International Conference on Learning Representations, 2021.

- Nikola Kovachki, Zongyi Li, Burigede Liu, Kamyar Azizzadenesheli, Kaushik Bhattacharya, Andrew Stuart, and Anima Anandkumar. Neural operator: learning maps between function spaces with applications to pdes. Journal of Machine Learning Research, 2023.

- Miguel Liu-Schiaffini, Julius Berner, Boris Bonev, Thorsten Kurth, Kamyar Azizzadenesheli, and Anima Anandkumar. Neural operators with localized integral and differential kernels. In Proceedings of the 41st International Conference on Machine Learning, 2024.

- Kamyar Azizzadenesheli, Nikola Kovachki, Zongyi Li, Miguel Liu-Schiaffini, Jean Kossaifi, and Anima Anandkumar. Neural operators for accelerating scientific simulations and design. Nature Reviews Physics, 2024.

- Kangjie Li and Wenjing Ye. D-FNO: A decomposed Fourier neural operator for large-scale parametric partial differential equations. Computer Methods in Applied Mechanics and Engineering, 2025.

- Junwoo Cho, Seungtae Nam, Hyunmo Yang, Seok-Bae Yun, Youngjoon Hong, and Eunbyung Park. Separable physicsinformed neural networks. In Thirty-seventh Conference on Neural Information Processing Systems, 2023.

- Yisi Luo, Xile Zhao, Zhemin Li, Michael K. Ng, and Deyu Meng. Low-rank tensor function representation for multidimensional data recovery. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2024.

- Jianli Wang and Xile Zhao. Functional transform-based low-rank tensor factorization for multi-dimensional data recovery. In 18th European Conference on Computer Vision, 2024.

- Sai Karthikeya Vemuri, Tim Bu ̈chner, Julia Niebling, and Joachim Denzler. Functional tensor decompositions for physicsinformed neural networks. In International Conference on Pattern Recognition, 2025.

- Dejia Xu, Peihao Wang, Yifan Jiang, Zhiwen Fan, and Zhangyang Wang. Signal processing for implicit neural representations. In Advances in Neural Information Processing Systems, volume 35, 2022.

- Sourav Pal, Harshavardhan Adepu, Clinton Wang, Polina Golland, and Vikas Singh. Implicit representations via operator learning. In Forty-first International Conference on Machine Learning, 2024.

- Matthew Tancik, Pratul Srinivasan, Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, Ravi Ramamoorthi, Jonathan Barron, and Ren Ng. Fourier features let networks learn high frequency functions in low dimensional domains. In International Conference on Neural Information Processing Systems, 2020.

- Sifan Wang, Xinling Yu, and Paris Perdikaris. When and why PINNs fail to train: A neural tangent kernel perspective. Journal of Computational Physics, 2022.

- Andrea Bonfanti, Giuseppe Bruno, and Cristina Cipriani. The challenges of the nonlinear regime for physics-informed neural networks. In Advances in Neural Information Processing Systems, volume 37, 2024.

- Mike Nguyen and Nicole M ̈ucke. Optimal convergence rates for neural operators. ArXiv:2412.17518, 2025.

- Sven Dummer, Nicola Strisciuglio, and Christoph Brune. Rda-inr: Riemannian diffeomorphic autoencoding via implicit neural representations. SIAM Journal on Imaging Sciences, 2024.


## Medical Imaging and Bioinformatic

- Yisi Luo, Xile Zhao, Kai Ye, and Deyu Meng. Stinr: Deciphering spatial transcriptomics via implicit neural representation. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2025.

- Vivien Marx. Method of the year: spatially resolved transcriptomics. Nature Methods, 2021.

- Michal Byra, Charissa Poon, Tomomi Shimogori, and Henrik Skibbe. Implicit neural representations for joint decomposition and registration of gene expression images in the marmoset brain. In Medical Image Computing and Computer Assisted Intervention, 2023.

- Amirali Molaei, Amirhossein Aminimehr, Armin Tavakoli, Amirhossein Kazerouni, Bobby Azad, Reza Azad, and Dorit Merhof. Implicit neural representation in medical imaging: A comparative survey. In Proceedings of the IEEE/CVF International Conference on Computer Vision Workshops, 2023.

- Albert W. Reed, Hyojin Kim, Rushil Anirudh, K. Aditya Mohan, Kyle Champley, Jingu Kang, and Suren Jayasuriya. Dynamic ct reconstruction from limited views with implicit neural representations and parametric motion fields. In 2021 IEEE/CVF International Conference on Computer Vision, 2021.

- Edward T. Reehorst and Philip Schniter. Regularization by denoising: Clarifications and new interpretations. IEEE Transactions on Computational Imaging, 2019.

- Vasiliki Sideri-Lampretsa, Julian McGinnis, Huaqi Qiu, Magdalini Paschali, Walter Simson, and Daniel Rueckert. SINR: Spline-enhanced implicit neural representation for multi-modal registration. In International Conference on Medical Imaging with Deep Learning, 2024.

- Tianci Song, Charles Broadbent, and Rui Kuang. GNTD: reconstructing spatial transcriptomes with graph-guided neural tensor decomposition informed by spatial and functional relations. Nature Communications, 2023.

- Yu Sun, Jiaming Liu, Mingyang Xie, Brendt Wohlberg, and Ulugbek S. Kamilov. Coil: Coordinate-based internal learning for tomographic imaging. IEEE Transactions on Computational Imaging, 2021.

- Romain Vo, Julie Escoda, Caroline Vienne, and E ́tienne Decencie`re. Neural field regularization by denoising for 3d sparseview x-ray computed tomography. In 2024 International Conference on 3D Vision, 2024.

- Jelmer M Wolterink, Jesse C Zwienenberg, and Christoph Brune. Implicit neural representations for deformable image registration. In Proceedings of The 5th International Conference on Medical Imaging with Deep Learning, volume 172, 2022.

- Qing Wu, Chenhe Du, Xuanyu Tian, Jingyi Yu, Yuyao Zhang, and Hongjiang Wei. Moner: Motion correction in undersampled radial MRI with unsupervised neural representation. In The Thirteenth International Conference on Learning Representations, 2025.

- Qing Wu, Yuwei Li, Yawen Sun, Yan Zhou, Hongjiang Wei, Jingyi Yu, and Yuyao Zhang. An arbitrary scale super-resolution approach for 3d mr images via implicit neural representation. IEEE Journal of Biomedical and Health Informatics, 2023.

- Qing Wu, Yuwei Li, Lan Xu, Ruiming Feng, Hongjiang Wei, Qing Yang, Boliang Yu, Xiaozhao Liu, Jingyi Yu, and Yuyao Zhang. Irem: High-resolution magnetic resonance image reconstruction via implicit neural representation. In Medical Image Computing and Computer Assisted Intervention, 2021.

- Hongze Yu, Jeffrey A. Fessler, and Yun Jiang. Bilevel optimized implicit neural representation for scan-specific accelerated mri reconstruction. Arxiv: 2502.21292, 2025.

- Ellen D. Zhong, Tristan Bepler, Joseph H. Davis, and Bonnie Berger. Reconstructing continuous distributions of 3d protein structure from cryo-em images. In International Conference on Learning Representations, 2020.

- Qingtian Zhu, Yumin Zheng, Yuling Sang, Yifan Zhan, Ziyan Zhu, Jun Ding, and Yinqiang Zheng. Suica: Learning super-high dimensional sparse implicit neural representations for spatial transcriptomics. Arxiv: 2412.01124, 2024.

- Veronika A. Zimmer, Kerstin Hammernik, Vasiliki Sideri-Lampretsa, Wenqi Huang, Anna Reithmeir, Daniel Rueckert, and Julia A. Schnabel. Towards generalised neural implicit representations for image registration. In Medical Image Computing and Computer Assisted Intervention, 2024.

- Uthsav Chitra, Brian J. Arnold, Hirak Sarkar, Kohei Sanno, Cong Ma, Sereno Lopez-Darwin, and Benjamin J. Raphael. Mapping the topography of spatial gene expression with interpretable deep learning. Nature Methods, 2025.

- Jiayue Chu, Chenhe Du, Xiyue Lin, Xiaoqun Zhang, Lihui Wang, Yuyao Zhang, and Hongjiang Wei. Highly accelerated mri via implicit neural representation guided posterior sampling of diffusion models. Medical Image Analysis, 2025.

- Regev Cohen, Michael Elad, and Peyman Milanfar. Regularization by denoising via fixed-point projection (RED-PRO). SIAM Journal on Imaging Sciences, 2021.

- Berk Iskender, Sushan Nakarmi, Nitin Daphalapurkar, Marc L. Klasky, and Yoram Bresler. Rsr-nf: Neural field regularization by static restoration priors for dynamic imaging. Arxiv: 2503.10015, 2025.

- Shang Li, Kuo Gai, Kangning Dong, Yiyang Zhang, and Shihua Zhang. High-density generation of spatial transcriptomics with stage. Nucleic Acids Research, 2024.


## Geosciences and Remote Sensing

- Kaiwei Zhang, Dandan Zhu, Xiongkuo Min, and Guangtao Zhai. Implicit neural representation learning for hyperspectral image super-resolution. IEEE Transactions on Geoscience and Remote Sensing, 2023.

- Huan Chen, Wangcai Zhao, Tingfa Xu, Guokai Shi, Shiyun Zhou, Peifu Liu, and Jianan Li. Spectral-wise implicit neural representation for hyperspectral image reconstruction. IEEE Transactions on Circuits and Systems for Video Technology, 2024.

- Ge Meng, Jingjia Huang, Yingying Wang, Zhenqi Fu, Xinghao Ding, and Yue Huang. Progressive high-frequency reconstruction for pan-sharpening with implicit neural representation. In Proceedings of the AAAI Conference on Artificial Intelligence, 2024.

- Guochao Chen, Jiangtao Nie, Wei Wei, Lei Zhang, and Yanning Zhang. Arbitrary-scale hyperspectral image super-resolution from a fusion perspective with spatial priors. IEEE Transactions on Geoscience and Remote Sensing, 2024.

- Yu-Jie Liang, Zihan Cao, Shangqi Deng, Hong-Xia Dou, and Liang-Jian Deng. Fourier-enhanced implicit neural fusion network for multispectral and hyperspectral image fusion. In Advances in Neural Information Processing Systems , 2024.

- Ting Wang, Jizhou Li, Michael K. Ng, and Chao Wang. Nonnegative matrix functional factorization for hyperspectral unmixing with nonuniform spectral sampling. IEEE Transactions on Geoscience and Remote Sensing, 2024.

- Wenbin Gao, Dawei Liu, Wenchao Chen, Mauricio D. Sacchi, and Xiaokai Wang. NeRSI: Neural implicit representations for 5d seismic data interpolation. Geophysics, 2025.

- Shengrui Wang, Yisi Luo, Sanfu Li, Jiangjun Peng, and Bangyu Wu. Efficient seismic random noise attenuation via kan-empowered neural low-rank representation. IEEE Transactions on Geoscience and Remote Sensing, 2025.

- Jian Sun, Kristopher Innanen, Tianze Zhang, and Daniel Trad. Implicit seismic full waveform inversion with deep neural representation. Journal of Geophysical Research: Solid Earth, 2023.

- Bo Du, Jian Sun, Anqi Jia, Ning Wang, and Huaishan Liu. Physics-informed robust and implicit full waveform inversion without prior and low-frequency information. IEEE Transactions on Geoscience and Remote Sensing, 2024.

- Xiaoduo Pan, Deliang Chen, Baoxiang Pan, Xiaozhong Huang, Kun Yang, Shilong Piao, Tianjun Zhou, Yongjiu Dai, Fahu Chen, and Xin Li. Evolution and prospects of earth system models: Challenges and opportunities. Earth-Science Reviews, 2025.


