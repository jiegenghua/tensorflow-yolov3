1. train

```
python train.py
```
2. test
```
python evaluate.py
```
3. mAP calculation
```
cd mAP
python main.py -na
```

######    ps: **train.txt**, **test.txt** are separately the training set and testing set, which logged down the image information, box positions, and labels. If you want to use the code, just try to make sure your train.txt and test.txt have the same format as here. Then put your anchors in the ./data/anchors/ and the class name in ./data/classes. The anchors are obtained by kmeans.py. 
Checkpoint can't be uploaded due to the speciality of the file inside. If you want to test, you have to retrain the model and then test because I can't upload my model.
