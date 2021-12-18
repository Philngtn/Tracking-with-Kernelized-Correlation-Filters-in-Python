# Tracking with Kernelized Correlation Filters in Python

The paper pinpoints the problem of modern tracking is under-sampling of negative samples, and then introduces the analytic model to overcome that constraint. By figuring out the properties of circulant matrices, which can be diagonalizable with Discrete Fourier Transform, the computation and storage of classifier can be reduced by several orders of magnitude. Moreover, authors also derive a new kernelized correlation filter (KCF) and a linear multi-channel filter (DCF), which has matched the performance of non-linear filter but still maintain a very low computational complexity. Both filters outperform top-ranking tracker such as Struck or TLD, while comfortably running at hundreds frames-per-second. 

Keywords—Visual tracking, circulant matrices, discrete Fourier transform, kernel methods, ridge regression, correlation filters

# PROJECT STATUS

Finished

## Project Screen Shot(s)


![image](https://user-images.githubusercontent.com/60360984/146629193-df4f58b1-451e-4261-ad3d-1cc4b9333f97.png)
Figure 1 Object Tracking with on Liquor sequence

![image](https://user-images.githubusercontent.com/60360984/146629199-98a92131-ddfa-4350-bb16-87bf5138d413.png)
Figure 2 Object Tracking with on Girl sequence
