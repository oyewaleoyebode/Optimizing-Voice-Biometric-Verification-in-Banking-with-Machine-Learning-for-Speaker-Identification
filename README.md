# Optimizing Voice Biometric Verification in Banking with Machine Learning for Speaker Identification
Voice-Biometric-APCC2024

**Author**: Oyebode Oluwatobi Oyewale  
**Affiliation**: Cyber Resilience Laboratory, NAIST (Japan)  
**Conference**: APCC 2024  
**DOI**: [10.1109/APCC62576.2024.10768085](https://doi.org/10.1109/APCC62576.2024.10768085)


## Abstract  
Biometric verification is essential for secure identity verification and authentication during banking transactions, using fingerprints, facial features, irises, and voices. Voice biometrics is a promising alternative among these methods, owing to its potential for robust and convenient user authentication.

However, their effectiveness is significantly challenged by variations in the voice caused by different device configurations and environmental conditions. These variations can reduce speaker identification effectiveness and undermine voice-based systems’ reliability in securing online transactions. This study addresses these challenges for an effective comparative solution by focusing on the difficulties posed by voice variations due to differences in device hardware, microphone quality, and environmental noise.

Our approach employs machine learning techniques using advanced speech enhancement methods to improve the consistency and accuracy of voice biometric verification across diverse devices. Specifically, we employ an adaptive filter model that enhances signal extraction, noise suppression, and predictive precision. Furthermore, our empirical demonstration demonstrated that the adaptive filter significantly improved the accuracy of voice biometric systems by mitigating the impact of device-induced voice variations. In addition, we evaluate the performance of this model using a range of metrics.  

## Background  
Voice biometrics provide secure authentication but can be influenced by noise, device variations, and environmental factors. Traditional noise reduction methods often struggle with rapid changes; therefore, this study introduces adaptive filtering to enhance the speech quality. Our approach improves reliability and ensures consistent verification across various conditions. This study emphasizes the need for robust speech enhancement techniques to address real-world noise challenges, as illustrated in Figure 1.

<p align="center">
  <img src="https://github.com/user-attachments/assets/7eb6e030-1eae-4d30-b59d-55e3c39b1ec7" alt="System Architecture" width="600"/>
</p>


## Proposed Methodology  
This study leverages machine learning by integrating a hybrid Convolutional Neural Network (CNN)–Long Short-Term Memory (LSTM) model to enhance voice biometric verification. The CNN layers extract spatial features, such as phonemes and intonations, whereas the LSTM layers capture temporal dependencies, ensuring robust speaker identification.

To further improve system reliability, adaptive filtering techniques mitigate inter-speaker variations and environmental noise. Additionally, speech enhancement algorithms refine voice clarity and suppress noise, thereby providing high-quality input for accurate biometric analysis.

<p align="center">
  <img src="https://github.com/user-attachments/assets/41217422-ec15-4fd5-8ea8-e9f7353851c0" alt="Speech Enhancement" width="600"/>
</p>


The proposed system, illustrated in Figure 2, focuses on adapting mobile devices for voice biometric verification during banking. The system ensures secure and accurate authentication across diverse devices by verifying users based on vocal characteristics rather than on speech content. This approach combines advanced machine-learning and speech-enhancement techniques to address device-related variations, ultimately improving the consistency and security of voice-based authentication systems.


## Results  
The evaluations presented in Table 1 compare Implicit Wiener Filtering, Spectral Subtraction, and Adaptive Filtering methodologies for speech enhancement in voice biometric applications. The Adaptive Filter achieved the highest precision, recall, and F1-score with 97% accuracy, outperforming the others. Spectral Subtraction performed well, but showed slight variations, whereas Implicit Wiener Filtering had the lowest performance.

- As shown in Figure 3, the ROC curves highlight the Adaptive Filter's superior true positive rate and lower false positive rate, particularly in noisy environments.

<p align="center">
  <img src="https://github.com/user-attachments/assets/5e128f0d-938c-4ec1-941f-597cc5e7ea7d" alt="System Architecture" width="600"/>
</p>

- These results confirm that Adaptive Filtering is the most effective method for enhancing voice biometric verification against noise and device variation.

<p align="center">
  <img src="https://github.com/user-attachments/assets/29977a1e-c2eb-4cf8-bfaf-e8cb72c72da3" alt="ROC Curve" width="600"/>
</p>

## Conclusion  
This study identified the adaptive filter as the most effective for voice biometric verification, achieving 97% accuracy while preserving the speech quality and reducing distortion. These findings improve speaker identification by addressing device variations and environmental noise, thereby ensuring a more reliable biometric authentication.

Future efforts will focus on real-time deployment, optimizing computational efficiency, and integrating deep learning and multimodal biometrics to improve the system's robustness.

## Citation

If you wish to cite this work:

```bibtex
@inproceedings{oyewale2024voicebiometric,
  title={Optimizing Voice Biometric Verification in Banking with Machine Learning for Speaker Identification},
  author={Oyewale, Oyebode Oluwatobi and Hossain, M. D. and Taenaka, Y. and Kadobayashi, Y.},
  booktitle={2024 IEEE 29th Asia Pacific Conference on Communications (APCC)},
  pages={377--384},
  year={2024},
  organization={IEEE},
  doi={10.1109/APCC62576.2024.10768085}
}
