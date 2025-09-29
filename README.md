This is an adaptive threshold applciation for better classsification accuracy and industrial diagnosis

Datasets used in this code is too large to be uploaded. Here are links for the four public datasets


ESC10
https://www.kaggle.com/datasets/sreyareddy15/esc10rearranged

US8K
https://urbansounddataset.weebly.com/urbansound8k.html

IDMT Engine
https://zenodo.org/records/7551261

MIMII Pump
https://www.kaggle.com/datasets/senaca/mimii-pump-sound-dataset


1. Now let's do this step by step firt u need to downlowad the four datsets and put theme to data foler then the structure will like this 
<img width="143" height="172" alt="image" src="https://github.com/user-attachments/assets/91927de8-b99b-4efc-8d92-c280e5fb3b4f" />

<!-- 这是注释，在 GitHub 上不会显示 -->
<!--
adaptive-threshold
    ...
    processing
    data
        engine 
        pump
        esc10
        us8k -->
2. after this, put the downloaded files for each category into audio folder, here is a exmapel of engine folder. 
engine
<img width="178" height="129" alt="image" src="https://github.com/user-attachments/assets/e1c938f6-75fd-4ac3-bf0a-281bd9cb0098" />

audio
    broken
        atmo_high_0.wav
        ...
    good
    heavy_load

 4. let's run /precess/a_datapreprocess.py, u will get  .npy file in npy folder for later training and .jpg file in image for visualization
    the strcture of the folder will be like this
<img width="178" height="129" alt="image" src="https://github.com/user-attachments/assets/e1c938f6-75fd-4ac3-bf0a-281bd9cb0098" />
    
audio
    broken
    good
    heavy_load
img    
    broken
    good
    heavy_load
npy
    broken
    good
    heavy_load
this is an exaple jpg file, x is time frame, y is frequency channel.
![atmo_high_0](https://github.com/user-attachments/assets/e00e92e4-b4a0-4a96-b053-bd4ffbaaa7d8)



 
