# Sparse Channel Code based Filter Bank Review for Faster Than Nyquist Communication and DNN Calculation  

Link to my presentation related to Sparse filter Bank approach https://github.com/Lcrypto/Topology-Signal-Processing/blob/master/MMMA-2019_19_8_19_final.pdf
Sparse Dictionary Optimization for Faster-than-Nyquist Sampling. The presentation was delivered at The 5th International Conference on Matrix Methods In Mathematics and applications (MMMA 2019) in August 2019, and you can find more information about the conference at https://www.skoltech.ru/en/2019/08/the-5th-international-conference-on-matrix-methods-in-mathematics-and-applications/.
Because of its excellent performance and generally satisfied assumptions, the technology of sFFT was named one of the ten breakthrough technologies in MIT Technology Review in 2012.

Very good review for different methods at paper of Professor Li Bin [On Performance of Sparse Fast Fourier Transform Algorithms Using the Aliasing Filter](https://www.mdpi.com/2079-9292/10/9/1117) 
and all platforms contained in [folder](https://github.com/Lcrypto/Sparse_Filter_Bank_Review/tree/main/Sparse%20Filter%20Bank%20platforms%20and%20exp%20data).



## On Performance of Sparse Fast Fourier Transform Algorithms Using the Aliasing Filter
Computing the sparse fast Fourier transform (sFFT) has emerged as a critical topic for a long time because of its high efficiency and wide practicability. More than twenty different sFFT algorithms compute discrete Fourier transform (DFT) by their unique methods so far. In order to use them properly, the urgent topic of great concern is how to analyze and evaluate the performance of these algorithms in theory and practice. This paper mainly discusses the technology and performance
of sFFT algorithms using the aliasing filter. In the first part, the paper introduces the three frameworks: the one-shot framework based on the compressed sensing (CS) solver, the peeling framework based on the bipartite graph and the iterative framework based on the binary tree search. Then, we obtain the conclusion of the performance of six corresponding algorithms: the sFFT-DT1.0, sFFT-DT2.0, sFFT-DT3.0, FFAST, R-FFAST, and DSFFT algorithms in theory. In the second part, we make two categories of experiments for computing the signals of different SNRs, different lengths, and different sparsities by a standard testing platform and record the run time, the percentage of the signal sampled, and the L0, L1, and L2 errors both in the exactly sparse case and the general sparse case. The results of these performance analyses are our guide to optimize these algorithms and use them selectively.
