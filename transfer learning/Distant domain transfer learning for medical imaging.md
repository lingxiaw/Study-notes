### Abstract
- This study is related to a not well-investigated but important transfer learning problem, termed Distant Domain Transfer Learning (DDTL). 
- In this study, we develop a DDTL model for COVID-19 diagnose using unlabeled image data sets as the source data, and a small set of labeded COVID-19 lung CT as the target data. 

### Introduction
- The proposed framework contains two parts: semantic segmentation and (distant feature fusion) DFF
- It can perform knowlegde transfer between seemingly unrealted domains
<img src="https://user-images.githubusercontent.com/19678358/114207601-8a209780-992a-11eb-8ba1-40a85adcc03a.PNG" width= "100" height="100">

![Capture](https://user-images.githubusercontent.com/19678358/114207601-8a209780-992a-11eb-8ba1-40a85adcc03a.PNG)


### Related Work
#### A. conventional transfer learning

There are two types of accessible transfer learning: feature-based and instance-based.
- Feature-based: map source features and target features into a **common feature space** where the **distribution mismatch is minimized**;
- Instance-based: discover source instances **similar to** target instances, so that **highly unrelated source samples would be eliminated**. 

Both of them assume that the source domain and target domain share a fairly strong connection.

#### B. Distant Domain Transfer Learning (DDTL)
- DDTL focuses on using the knowledge in other domains to imrpove the performance of the target task.
- The inspiration of DDTL is from the ability of human beings to learn new things by bridging knowledge acquired from several seemingly independent things, e.g., a human how knows birds and airplanes can recognize a rocket even without seeing any rockets previously.



