



### Content

The **Colab_notebooks** folder contains the training steps of the project.

The **runs** folder contains the output of training and testing.

The **utils** and **models** folders contain the modified model of the project.

### Instruction to Reproduce our Training

To reproduce some training experiments, use the notebooks in the provided **Colab_notebooks** folder or the **Colab_notebooks** zip file.

### Instructions to Training from Scratch

##### Modified YOLOv7

```
pip install -r requriements.txt
python train.py
```

##### Modified YOLOv7-e6e

```
pip install -r requriements.txt
python train_aux.py
```

##### Detect

```
pip install -r requriements.txt
python detect.py
```

##### Test

```
pip install -r requriements.txt
python test.py
```

