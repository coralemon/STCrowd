
# STCrowd

 This repository is for STCrowd dataset baseline and official implement for **STCrowd: A Multimodal Dataset for Pedestrian Perception in Crowded Scenes**.

## Dataset 
To be add for our website...

## Installation

### Requirements
- PyTorch >= 1.2 
- yaml
- mmcv
- mmdet
- mmdet3d
- mmpycocotools

## Data Preparation


```
./
└── Path_To_STCrowd/
    ├──split.json
    ├──anno
        ├── 1.json
        ├── 2.json
        └── ...
    ├── left        
        ├── 1	
        |   ├── XXX.jpg
        |   ├── XXX.jpg
        │   └── ...
        ├── 2 
        ├── ...
    ├── right    
        ├── 1	
        |   ├── XXX.jpg
        |   ├── XXX.jpg
        │   └── ...
        ├── 2 
        ├── ...
    ├── pcd        
        ├── 1	
        |   ├── XXX.bin
        |   ├── XXX.bin
        │   └── ...
        ├── 2 
            ├── XXX.bin
            ├── XXX.bin
            └── ...
```
## Dataset convert
We provide the convert code for data converting.
eg. convert for **STCrowd_infos_train.pkl**.
```
python STCrowd_conver.py --path  Path_To_STCrowd --split 'train'
```
