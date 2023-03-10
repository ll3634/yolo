



# Content

The **Colab_notebooks** folder contains the training steps of the project.

The **runs** folder contains the output of training and testing.

The **utils** and **models** folders contain the modified model of the project.

# Instruction to Reproduce our Training

To reproduce some training experiments, use the notebooks in the provided **Colab_notebooks** folder or the **Colab_notebooks** zip file.

# Instructions to Training from Scratch

### Modified YOLOv7
Download the weight from https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt

Put it in /
```
pip install -r requriements.txt
python train.py
```

### Modified YOLOv7-e6e
Download the weight from https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7-e6e.pt

Put it in /
```
pip install -r requriements.txt
python train_aux.py
```

### Detect
Download the weight from https://drive.google.com/u/0/uc?id=1UzWx7n0mXnYGMxm02zKNcp4_-1NHm6GV

Put it in runs/train/exp20
```
pip install -r requriements.txt
python detect.py
```

### Test
Download the weight from https://drive.google.com/u/0/uc?id=1UzWx7n0mXnYGMxm02zKNcp4_-1NHm6GV

Put it in runs/train/exp20
```
pip install -r requriements.txt
python test.py
```

