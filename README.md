# Region Proposal Algorithms to Train Support Vector Machines and Convolutional Neural Networks for Mass Detection in Mammograms

**Contributors**: Jaime Simarro Viana, Zohaib Salahuddin, Ahmed Gouda, Anindo Saha  

**Problem Statement**: Extract candidate regions of interest (ROI) for mass detection in mammograms, that are subsequently to-be-used for training a classifier (eg. *support vector machines*, *convolutional neural networks*, etc.) 
 
**Dataset**: [*INbreast* Digital Mammographic Dataset](https://pubmed.ncbi.nlm.nih.gov/22078258/) - 115 cases (410 images). [[Download](https://drive.google.com/file/d/19n-p9p9C0eCQA1ybm6wkMo-bbeccT_62/view) - Credit: @wentaozhu]
 
## Preprocessing (*Contrast-Limited Adaptive Equalization)*
![Preprocessing](reports/images/preprocessing.png)
   
     
## Morphological Enhancement (*Multi-Scale Morphological Sifting*)  
![MMS](reports/images/mms.png)

    
## Unsupervised Segmentation (*SLIC Superpixels*) 
![SLIC Superpixels](reports/images/slic.png) 
 

## Supervised Patch Extraction (*Class-Weighted Sampling*)
![Patch Extraction](reports/images/patch.png) 

## References
● Hang M. et al. (2019) "*Multi-Scale Sifting for Mammographic Mass Detection and Segmentation*", Biomedical Physics & Engineering Express, 5-2. DOI:10.1088/2057-1976/aafc07  
● Radhakrishna A. et al. (2010) "*SLIC Superpixels Compared to State-of-the-Art Superpixel Methods*", IEEE TPAMI. DOI:10.1109/TPAMI.2012.120  
● Moreira IC et al. (2012) "INbreast: Toward A Full-Field Digital Mammographic Database", Acad Radiol. 2012;19(2):236–248. DOI:10.1016/j.acra.2011.09.014
