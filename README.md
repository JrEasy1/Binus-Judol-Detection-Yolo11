# Binus-Judol-Detection-Yolo11
Christian Antonius Anggaresta - 2602179214  
Jonathan Lucas Fontana - 2602159723  
Farrel Adyatma Alimin - 2602216906  


The actual deep learning models are too big in github, so we will be saving it in huggingface  
We also added the dataset used both in COCO and YOLO format  
HuggingFace = https://huggingface.co/spaces/JrEasy/Judol_Push_model/tree/main  
*Note = Because the demo host in huggingface is using the free basic-cpu, I advise to use a very short video video detection(1 - 5 seconds), image detection should be fine... For longer videos i suggest to just use colab gradio

(All Colab Links to .ipynb files are in documentation)
Link Docs = https://docs.google.com/document/d/1sRhai6kxePchqMiQZSr8qkD4HzZNdu1G4qUgvAjcoGM/edit?tab=t.0  


YOLO11 Model = best.pt  
RTDETR Model = model.safetensors  
To use our models you can also just use:  
https://huggingface.co/spaces/JrEasy/Judol_Push_model/resolve/main/best.pt // For YOLO11  
https://huggingface.co/spaces/JrEasy/Judol_Push_model/resolve/main/model.safetensors // For RT-DETR  

Running all the codes will need dependencies:    
os  
numpy  
cv2  
matplotlib  
skimage  
roboflow  
ultralytics  
yaml  
IPython  
sklearn  
joblib  
zipfile  
accelerate  
torchmetrics  
albumentations>=1.4.5  
requests  
torch  
supervision // [roobflow](https://github.com/roboflow/supervision.git)  
google.colab  
pprint  
dataclasses  
transformers   
gradio
imageio
