### EMD techniques

EMD techniques that are well suited for non-stationary and non-linear processes without replying on extrinsic functional or simplifying assumption. 

This paper  https://www.pnas.org/doi/epdf/10.1073/pnas.0701020104   recommends using Empirical Mode Decomposition (EMD) for 
Determining Intrinsic Trend for non linear and nonstationary time series. This method allows us to decompose the time series to obtain
components which help you analyze / understand data inherent features. 

This has been implemented in this this library https://emd.readthedocs.io/en/stable/

--

This paper which discusses best practices around the use of EMD: https://www.nature.com/articles/s41598-020-72193-2  
encourages the use of newer variants of the methods that overcomes some of the shortcomings of the original method. 

https://www.mathworks.com/help/signal/ref/emd.html 
