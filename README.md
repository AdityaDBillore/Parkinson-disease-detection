This repository illustrates and debates the study of three machine learning algorithms viz., logistic regression, decision tree classification and support vector machine and their capability to understand and foretell the fatalities of patients with Parkinson’s disease. The dataset utilized, enfolds some medical evidence and facts of patients comprising of speech recordings at various frequencies which will foretell the person suffering from Parkinson’s disease. Using this material, we will survey the dataset and classify the class variable by means of several machine learning prototypes and uncover which algorithm is best suited for this dataset. The principal intention is to evaluate the accuracy by classifying the data with regards to efficacy and effectiveness of each algorithm in terms of accuracy and precision.

Parkinson’s is the fastest emerging neurological condition in the world, and presently there is no cure. 1 in 37 people alive today in the UK will be detected with Parkinson’s on their lifetime. Out estimations show that around 145,000 people live with a Parkinson’s diagnosis in the UK in 2020. Broken down within the UK, for 2020, England comprises of 121,000 patients suffering from Parkinson’s. Whereas Scotland has 12,400 patients, Wales with 7,600 and 3,900 people are suffering from Northern Ireland. 

![Picture1](https://user-images.githubusercontent.com/84669433/161253606-67684143-6b4b-4e80-b596-986960692150.jpg)

The dataset that is chosen for this report is acquired from Kaggle titled as ‘Parkinson’s disease classification’. This database comprises of 754 attributes and 756 instances. The attribute characteristics are integer and real. There are as such no missing values found in the dataset and it is characterized as a multivariate dataset. The column descriptions are as follows:
	Baseline features: Col3 to Col23
	Intensity parameters: Col 24 to Col 26
	Format frequencies: Col27 to Col30
	Bandwidth parameters: Col31 to Col34
	Vocal fold: Col35 to Col56
	MFCC: Col57 to Col140
	Wavelet features: Col141 to Col322
	TQWT features: Col323 to Col754
	Class: Col755
MFCC stands for Mel-frequency cepstral coefficients. They are curbed from a type of cepstral illustration of the audio clip. And TQWT symbolises Tunable Q-Factor Wavelet Transform. It is a constant Q transform that is easily invertible, modestly oversampled, and satisfies Parseval’s energy theorem.

![Picture2](https://user-images.githubusercontent.com/84669433/161253862-0e6ca40b-01d4-43ba-a6a7-9c07bad25b26.jpg)

The data used in this study were gathered from 188 patients with PD (107 men and 81 women) with ages fluctuating from 33 to 87 at the Department of Neurology in Cerrahpasa Faculty of Medicine, Istanbul University. The control group comprises of 64 healthy individuals (23 men and 41 women) with ages ranging between 41 and 82. 
During the data collection procedure, the microphone is set to 44.1 KHz and following the physician’s examination, the continual phonation of the vowel /a/ was gathered from each subject with three repetitions. Out of total patients, approximately 390 are males and the rest are females. The second column from the dataset labels the gender of patients. As perceived in the figure above class 1 defines men whereas 0 designates women.

![Picture3](https://user-images.githubusercontent.com/84669433/161254146-f2c15369-1b3d-43ed-bba1-145665331dd6.jpg)

As shown in the above figure, it depicts the count of the target. It can be observed that out of 756 cases, more than 500 patients have been suffered from Parkinson’s disease. However, less than 200 patients don’t have Parkinson’s disease.

Various speech signal processing algorithms including Time Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform based Features, Vocal Fold Features and TWQT features have been applied to the speech recordings of Parkinson's Disease (PD) patients to extract clinically useful information for PD assessment. The link of the dataset is mentioned below in the references.
