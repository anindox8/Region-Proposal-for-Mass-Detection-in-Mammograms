# Mammographic Region Proposal Algorithms for Training  
# Support Vector Machines and Convolutional Neural Networks

**Problem Statement**: Fully supervised, multi-class 3D brain segmentation in T1 MRI. 
 
**Data**: *Label 0*: Background; *Label 1*: Cerebrospinal Fluid (CSF); *Label 2:* Gray Matter (GM); *Label 3:* White Matter (WM) [10/5/3 : Train/Val/Test Ratio]
 
## Preprocessing (*Contrast-Limited Adaptive Equalization)*
![Preprocessing](reports/images/preprocessing.png)
   
     
## Morphological Enhancement (*Multi-Scale Morphological Sifting*)  
![MMS](reports/images/mms.png)

    
## Region-Of-Interest Segmentation (*SLIC Superpixels*) 
![SLIC Superpixels](reports/images/slic.png) 
 

## Patch Extraction (*Guided*)
![Patch Extraction](reports/images/patch.png) 
