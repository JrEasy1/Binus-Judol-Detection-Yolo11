# Binus-Judol-Detection-Yolo11

The actual deep learning models are too big in github, so we will be saving it in huggingface
HuggingFace = https://huggingface.co/spaces/JrEasy/Judol_Push_model/tree/main  
*Note = Because the demo host in huggingface is using the free basic-cpu, I advise to use a very short video video detection(1 - 5 seconds), image detection should be fine... For longer videos i suggest to just use your own colab gradio  

YOLO11 Model = best.pt  
RTDETR Model = model.safetensors  

Some dependencies you would need:    
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
