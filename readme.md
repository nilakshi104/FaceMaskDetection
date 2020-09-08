# FaceMaskDetection
* Repo contains two .ipynb notebooks 
  #### 1.Face_Mask_detector_for_Covid_19 : 
    Notebook contains Code for Data Preprocessing and Training using Face Detector Model built from scratch using Keras 
  #### 2.Face_mask_detection_using_MobileNetV2 :
    Notebook Contains Code for Data Preprocessing and Training using Finetuned MobileNetV2 model pretrained on imagenet dataset for face mask detection
    
### Results and Accuracy of *Face_Mask_detector_for_Covid_19* Notebook is discussed below:

  Face Mask Detector is built using multi-step approach by extracting **face of person using HaarCascades** & **passing it to mask detection model**

  ##### Architecture of mask detection model
  <img src="https://github.com/nilakshi104/FaceMaskDetection/blob/master/images/Screenshot%20from%202020-09-08%2018-32-21_n.png" width=500/img>

  #### Loss and Accuracy (F Score) of model
  <img src="https://github.com/nilakshi104/FaceMaskDetection/blob/master/images/Screenshot%20from%202020-09-08%2018-32-49.png" width=400/img>  <img src="https://github.com/nilakshi104/FaceMaskDetection/blob/master/images/Screenshot%20from%202020-09-08%2018-32-53.png" height= 200 width=400/img>
  
  #### Results
  
  1.Results on test data
  
  <img src="https://github.com/nilakshi104/FaceMaskDetection/blob/master/images/Screenshot%20from%202020-09-08%2018-33-02.png" height=500/img>
  
  2.Results on Random Images from google
  
  <img src="https://github.com/nilakshi104/FaceMaskDetection/blob/master/images/Screenshot%20from%202020-09-08%2018-33-29.png" height=500/img>
  
  3.If Face is not detected by Haar Cascades, whole image is fed to model and model performs fine on it
  
  <img src="https://github.com/nilakshi104/FaceMaskDetection/blob/master/images/Screenshot%20from%202020-09-08%2018-33-15.png" height=250/img>
  
### Results and Accuracy of *Face_mask_detection_using_MobileNetV2* Notebook is discussed below:
  #### Loss and Accuracy (F Score) of model
  <img src="https://github.com/nilakshi104/FaceMaskDetection/blob/master/images/Screenshot%20from%202020-09-08%2019-09-57.png" width=400/img>  <img src="https://github.com/nilakshi104/FaceMaskDetection/blob/master/images/Screenshot%20from%202020-09-08%2019-10-00.png" height= 200 width=400/img>
  
  #### Results
  <img src="https://github.com/nilakshi104/FaceMaskDetection/blob/master/images/Screenshot%20from%202020-09-08%2019-10-06.png" width=400/img> 
