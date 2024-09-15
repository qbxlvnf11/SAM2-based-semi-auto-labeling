SAM2-Based Semi-Auto Segmentation Labeling Using anylabeling
=============

#### - [SAM2 (Segment-Anything-2)](https://github.com/facebookresearch/segment-anything-2)
  
  - Universal segmentation tool: SAM is designed to work across different domains without task-specific tuning, making it highly generalizable.
  - High-quality masks: SAM produces high-resolution and accurate masks, making it a valuable tool for pixel-precise segmentation.
  - Zero-shot capabilities: SAM does not need retraining for new image types or segmentation tasks.
  - Prompt-based interaction (Points): The user can click on specific points to guide the model in segmenting objects.
  
#### - Data labeling tools: [anylabeling](https://github.com/vietanhdev/anylabeling)
  
  - Useful and convenient labeling tool that supports SAM2
  - Create a label using SAM2 installed in this tool

#### - Install and run anylabeling

```
conda create -n anylabeling python=3.12
conda activate anylabeling
pip install anylabeling
sudo apt-get update
apt-get install -y qt5-default libxcb-xinerama0-dev
sudo apt-get install -y qt5-default libxcb-xinerama0-dev
anylabeling
```

#### - How to semi-auto-labeling of segmentation dataset using anylabeling
  
  - Upload image folder: [File] -> [Open Dir] -> choose folder
    
<img src="https://github.com/user-attachments/assets/a0bc861b-af93-491b-9e29-a81833b3816b" width="90%"></img>

  - Semi-auto localization (click on specific points to guide the model in segmenting objects): [Auto Labeling] -> Choose the version of SAM2 -> Click on specific points
    
<img src="https://github.com/user-attachments/assets/3c498d7c-2b35-4d4f-ba07-2905c4ab4343" width="90%"></img>


  - 
