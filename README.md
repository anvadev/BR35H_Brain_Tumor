***
# <p align="right"> BRAIN TUMOR DETECTION</p>
### <p align='right'> Capstone Phase 5 Project</p>

### <p align = 'right'> Name: Ansel Vallejo </p>


***
_Source:_ <br>
  > **Dataset:** _Brain Tumor Detection_ <br>
  > **Author:** _Ahmed Hamada_ <br>
  > **Website:** _Kaggle_ <br>
  > **URL:** _https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection_ <br>
***
![image](https://github.com/anvadev/BR35H_Brain_Tumor/assets/50537930/92665cd2-f737-410f-9152-40010ee86513)


***
**Algorithm Implemented:** _Convolutional Neural Network ("CNN") (Deep Learning)_<br>
**Data type:** _Unstructured_ 

<br>

**Data Classification:** <br>
> **NO** (no tumor) - classified as **0** <br>
> **YES** (yes tumor) - classified as **1** <br>

**Model Used:** brain_tumor_base_100_epochs_64_basics.h5 <br>
**Model Accuracy:** approx. <b>99%</b>

**Brain Tumor Detection v.1.0.0 (Beta):** _Work in Progress_ <br>
***

  ## Overview <br>
<p align="justify">
  In the medical field, Brain tumor is seen as a serious, abnormal growth of cells in or near the brain that can be either benign, which is non-cancerous or malignant, which is cancerous. There are many treatments an individual with such tumor can receive, such as radiation therapy, chemotherapy, therapeutic drug, etc. Brain tumor can be seen via Magnetic Resonance Imaging (MRI) scanned images. Human error is prone to occur in any industry, and because of such error in the medical field can cost a life. To detect and identify whether there is an absence of abnormal cell growth without human intervention would be to build a robust deep learning model to help the medical practitioner properly classify a tumor from no tumor using over 3000 MRI scan trained images and validated images to help better serve the model.
  </p>
  <br>
  ## Business Problem <br>
<p align="justify">
  Healthcare providers not utilizing Convolutional Neural Network ("CNN") models to detect brain tumors face several business problems. One significant challenge is the potential lack of accurate and efficient diagnosis. CNN models have demonstrated their effectiveness in accurately identifying brain tumors from medical imaging data, such as MRI scans. By not leveraging CNN models, healthcare providers may struggle to achieve high diagnostic accuracy, relying on manual interpretation that can be prone to errors, leading to misdiagnosis or delayed diagnosis. Every life is precious and healthcare providers have a social responsibility to provide utmost care by improving their technology infrastructure and a CNN model that can deliver 99% accuracy. Due to the nature of the industry, every percentage of accuracy is valuable; no space for errors. 
</p>
<br>
<br>

## Purpose of Model Adoption
<p align="justify">
  The model serves as the first pair of eyes for health providers to detect whether a patient has a Brain Tumor at its early stages. Healthcare providers have a social responsibility to provide utmost care to its patients and by improving and or enhancing their technological infrastructure, by adopting this model, they can administer proper care with high accuracy while reducing cost for both the patient and healthcare provider, time it takes to diagnose, reduce human interpretability and subjectivity. On the other hand, the advantages associated with adopting this model would be efficient, accurate, reduction of cost for both parties, and improve the outcome of patient care.
</p>  

#### <i>Disadvantages of not adopting the model</i>
<p align="justify">
There are several key disadvantages of not adopting a model, as the one proposed:
<ul>
  <li> <b>Time</b> - CNN models can analyze large volumes of medical imaging data quickly, allowing for faster diagnosis and treatment planning. Without leveraging CNN models, healthcare providers may experience delays in diagnosing brain tumors, which can impact patient outcomes and increase healthcare costs.</li>
  <li> <b>Diagnostic</b> - CNN models have shown promising results in accurately identifying brain tumors from medical imaging data, such as MRI scans. By not utilizing CNN models, healthcare providers may face challenges in achieving high diagnostic accuracy. Manual interpretation of medical images by radiologists or other healthcare professionals may be prone to errors, leading to misdiagnosis or delayed diagnosis.</li>
  <li> <b>Detection</b> - Brain tumors can be challenging to detect in their early stages, as they may be small, have subtle features, or resemble normal brain tissue. Without a CNN model's ability to analyze data at a high resolution and identify subtle patterns, there is a higher risk of missing early-stage tumors. Early detection is crucial for better treatment outcomes and improved patient survival rates.</li>
</ul>  
</p>

#### <i>Advantages of model adoption</i>
<p align="justify">
There are several key advantages of adopting a model, as the one proposed:
<ul>
  <li> <b>Patient Outcomes</b> - Brain tumor detection using CNN models can significantly improve the accuracy and efficiency of diagnosis. By suggesting this model to stakeholders, you are advocating for a technology that can potentially detect brain tumors at an early stage, leading to better patient outcomes and increased chances of successful treatment.</li>
  <li> <b>Diagnostic Speed</b> - CNN models have the ability to process large amounts of medical imaging data quickly and accurately. By suggesting this model, you can highlight how it can expedite the diagnostic process, enabling radiologists and clinicians to make faster and more informed decisions. Reduced diagnosis time can lead to improved patient throughput, decreased waiting times, and increased overall operational efficiency.</li>
  <li> <b>Cost Reduction</b> - Early detection of brain tumors can result in cost savings for both patients and healthcare providers. Timely identification allows for less invasive and more targeted treatments, reducing the need for complex and expensive interventions. By implementing a brain tumor detection CNN model, stakeholders can potentially minimize healthcare costs and optimize resource allocation.</li>
   <li> <b>Social Responsibility</b> - Advocating for the use of a brain tumor detection CNN model demonstrates the organization's commitment to ethical and social responsibility. By implementing advanced technology to improve healthcare outcomes, stakeholders can contribute to the greater good and positively impact the lives of patients and their families.</li>
</ul>
</p>
<br>

## How are MRI Images classified before training and validation?
An MRI image to the current model is <i>A picture that is worth one word; either <b>YES</b>, or <b>NO</b>. Therefore, the images were separated into two sets; YES and NO, to help better prepare the model for training and validation.</i>

![image](https://github.com/anvadev/BR35H_Brain_Tumor/assets/50537930/58a20708-3198-42ce-9e8e-28571ec30b40)

As you can see, the images have been properly classified to their respective diagnosis. With this in mind, it can help better train the model to detect unforeseen images, assuming the model is functioning properly. 

<b>Presentation:</b> <br>
[LINK]
<b>Contributors:</b> <br>
https://github.com/anvadev/
***

_<p align="center">End of document</p>_

*** 
***

  
