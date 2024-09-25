# Introduction of HCE Dataset

The HCE (Hangzhou-Changsha Electrocardiogram) dataset is a comprehensive electrocardiogram dataset collected by our research team in Changsha, Hunan, and Hangzhou, Zhejiang, China. The data collection protocol required each participant to adopt three distinct postures—standing, sitting, and lying—each maintained for a minimum of 60 seconds. A total of 76 volunteers participated in the ECG signal acquisition, comprising 39 males and 37 females. The participants' ages ranged from 19 to 94 years, encompassing 45 young adults (aged 34 years and below), 26 middle-aged adults (aged 35 to 59 years), and 5 elderly individuals (aged 60 years and above).

We recorded the ECG data produced by each volunteer during the maintenance of each posture, storing these recordings in individual files with a sampling rate of 1000 Hz, resulting in a total of 228 ECG files. After excluding certain invalid files, we retained 215 valid ECG files. The reasons for invalid samples included circuit disconnections, lead misplacements, and program interruptions.

The last 60 seconds of ECG data from each file were divided into six segments, with each segment serving as an individual sample lasting 10 seconds, yielding a total of 1290 ECG samples. These samples were subsequently annotated by cardiology experts, with 16 samples identified as PVC (Premature Ventricular Contractions) and 12 samples classified as RBBB (Right Bundle Branch Block).

## License

This dataset is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/). You are free to use, share, and adapt the data, as long as you provide appropriate attribution and distribute any derivative works under the same license.

If you wish to use the HCE (Hangzhou-Changsha Electrocardiogram) dataset, please cite the article titled "SAPTSTA-AnoECG: A PatchTST-based ECG Anomaly Detection Method with Subtractive Attention and Data Augmentation."
