# [Channel Estimation]Research on Channel Estimation Method Based on Deep Learning in OFDM System [Attached MATLAB Code]

Introduction: In recent years, driven by market trends and the strong demand for mobile communication systems, 5G and 4G have become global focal points in the new generation of communication. Within the time-varying and frequency-varying (multipath fading channels) of mobile radio channels [1], estimating channel coefficients (gain) is crucial. This method utilizes deep learning techniques from image processing for channel estimation. Previous studies [2][3] have demonstrated that this estimation method surpasses conventional methods in accuracy. However, these simulations were limited in terms of channel environments; hence, the time-varying and frequency-varying conditions were not fully validated, which are essential for real channels. Figure 1 illustrates an example of channel gain fluctuations using OFDM. Here, the main parameters affecting fluctuations are the maximum Doppler frequency (f), channel model, and delay spread (σ). In previous research, each parameter was fixed; however, in real systems, all parameters change. Therefore, the actual channel fluctuations are more complex. In such cases, it becomes challenging for deep learning to train; thus, it may be difficult to estimate the channel. In multipath Rayleigh fading channels, when a signal is transmitted at time t = 0, the relationship between transmission time and received power is shown in Figure 2. Coefficients ',' represent the changes in received power gain and attenuation. The relationship between time and received power is indicated by its delay curve (e.g., TDL-A, TDL-B, TDL-C) [4]. In each profile, urban micro (UMi) and urban macro (UMa) delay spreads are defined.
Conclusions: For the SR network, interpolation accuracy surpasses that of LS and ideal LMMSE. It can address the impact of noise dependent on the input signal, which is the channel estimate obtained at the LS method-derived pilot signal locations in the SR network. Firstly, using the LMMSE method instead of the LS method is beneficial. This is because the accuracy of the LMMSE method is better than this. Secondly, it is useful to use a denoising network composed of CNN for noise elimination after SR network processing with deep learning networks. Thirdly, improvements to the SR network are beneficial due to its development in 2016. After completion, a large number of high-precision models were developed. We can apply these models to improve estimation accuracy (for example, by increasing precision when reducing the number of pilot signals (such as using Type A)). Additionally, using measurements from actual environments is beneficial for evaluation. Specifically, we will obtain channel information through radio wave propagation analysis using ray tracing methods, which helps in assessment.

## Images

![(Channel Estimation)Research on channel estimation method based on deep learning in OFDM system [Attached MATLAB code]](01.jpg)
![(Channel Estimation)Research on channel estimation method based on deep learning in OFDM system [Attached MATLAB code]](02.jpg)
![(Channel Estimation)Research on channel estimation method based on deep learning in OFDM system [Attached MATLAB code]](03.jpg)
![(Channel Estimation)Research on channel estimation method based on deep learning in OFDM system [Attached MATLAB code]](04.jpg)
![(Channel Estimation)Research on channel estimation method based on deep learning in OFDM system [Attached MATLAB code]](05.jpg)
![(Channel Estimation)Research on channel estimation method based on deep learning in OFDM system [Attached MATLAB code]](06.jpg)
![(Channel Estimation)Research on channel estimation method based on deep learning in OFDM system [Attached MATLAB code]](07.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
