# CNN-CIFAR10-Classification
CIFAR10 Classification using CNN. Model implemented with Keras + Tensorflow
CIFAR10 dataset classification from the Canadian Institue For Advanced Research (CIFAR). The dataset has 10 classes:
- Class 0: Airplane
- Class 1: Car
- Class 2: Bird
- Class 3: Cat
- Class 4: Deer
- Class 5: Dog
- Class 6: Frog
- Class 7: Horse
- Class 8: Ship
- Class 9: Truck


60,000 RGB images of 32x32 pixels will be used for train and test split.


## Highlights
- Tensorflow-Keras for the implementation
- Saved .h5 Model Weights for Replication (or improve with transfer learning)
- Accuracy Results (Last Epoch):
```
Model Evaluation (Higher is Better): 
--- Train Accuracy: 0.916
--- Test Accuracy: 0.831
```

## Potential Modifications
- Evaluate impact of using Augmented Data (Could worsten of generlize the performance)
- Translate to PyTorch for a more 'White-Box' approach

## Demo Images

### Train & Validation Loss
![image](https://user-images.githubusercontent.com/87340855/219354820-bbfea0fb-7360-46bc-a1fd-f79feba8fdf1.png)

### Random Set of Images Classified
![image](https://user-images.githubusercontent.com/87340855/219354915-3b652c51-04e1-424c-bdb5-cffff747813a.png)

### Confusion Matrix
![image](https://user-images.githubusercontent.com/87340855/219354962-caa49938-2cd4-47e9-9e2f-ad33657a6581.png)


## References
- Dataset: https://www.cs.toronto.edu/~kriz/cifar.html
