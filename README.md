# Vehicle Detection
this agent trained on classes of 'Cars','Motorcycles','Trucks','Buses' and 'Bicycles'

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.

```bash
pip install -r requirements.txt
```

## Train
run this command with custom parameters
```python
!python train.py --img 640 --batch 16 --epochs 50 --data data.yaml --weights yolov5m.pt
```

## Inference
after train model set weights file and source to detect vehicles
```python
!python detect.py  --weights https://drive.google.com/file/d/1-KyzJ3-DyKOlovG53aeyqkzRq-qt5dF0/view?usp=sharing --source /content/[SOURCE_PATH]
```python
