# TiDL_Project_S22

Multi-label Image Recognition is the task of predicting all the possible object labels that are present in an image. We use graph neural networks (GNNs) to capture label dependencies and structural information in the image.

## Instructions to Run:

**For training**:

```python3 demo_voc2007_gcn.py data/voc --image-size 448 --batch-size 16 --resume checkpoint/voc/model_best_92.5336.pth.tar --epochs 100```

**For evaluation**:

```python3 demo_voc2007_gcn.py data/voc --image-size 448 --batch-size 16 --resume checkpoint/voc/model_best_92.5336.pth.tar -e```


