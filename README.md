# Background-Noise-Suppression-in-Audio-Signals
This project aims to enhance audio quality in communication systems by tackling the common problem of background noise. Our approach uses Variational Mode Decomposition (VMD), Signal-to-Noise Ratio (SNR) estimation, and the Short-Time Fourier Transform (STFT) to deliver a real-time noise suppression solution. By leveraging both traditional and advanced signal processing techniques, this project provides a customizable and scalable model adaptable to various environments, from video conferencing to telecommunication.

# Abstract
We propose a dynamic algorithm that integrates modern signal processing and machine learning techniques to address background noise suppression in audio communication. Our evaluations show significant improvements in Signal-to-Noise Ratio (SNR), speech intelligibility, and overall perceptual quality over existing technologies. Designed for real-time processing, this project is adaptable to a range of applications, aiming to enhance professional communication quality.

# Related Work
The study references traditional methods such as spectral subtraction, Wiener filtering, and adaptive filtering. We also review recent advancements in deep learning models, including convolutional and recurrent neural networks. Research in Non-negative Matrix Factorization and speech enhancement algorithms further informs our project’s foundation.

# Proposed Methodology
- **Variational Mode Decomposition (VMD)**: Used to remove unnecessary low-noise frequencies that typically contribute less to the audio signal and are often noise.
- **Hurst Exponent**: Assesses long-term memory within time-series data, providing insights into the temporal structure of decomposed components.
- **Short-Time Fourier Transform (STFT)**: Enables time-frequency analysis by sliding a window along the signal to visualize frequency components over time.
- **SNR Estimation and Apriori SNR Filtering**: Ensures stability in SNR estimation, aiding effective noise reduction without compromising the original signal.
The combination of these techniques provides effective noise suppression and enhances the audio's quality.

# Implementation
Our algorithm has been implemented in MATLAB, featuring customizable parameters (e.g., lambda, beta1, beta2, and alpha) for precision control. Below is a sample workflow:
- Original Signal: Visual representation before processing
- After Applying VMD and Hurst Exponent: Filtered signal retaining only necessary components
- Spectrograms: Visualization of noise suppression results in different time frames
- Denoised Output Signal: Final signal after noise suppression
# Results
- Improved Signal Quality: Enhanced SNR, intelligibility, and perceptual audio quality.
- Computational Efficiency: The combination of VMD and STFT with SNR filtering allows for real-time processing suitable for live applications.
  
