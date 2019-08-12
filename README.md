# iris-analysis
Foreground and Background classification of iris data using CNN.

### Dataset creation

1. 50 iris images were used to create the dataset. 
2. From each image 5 patches for foreground and background were selected having length 28X28.
3. Class label 1 for foreground and class label 0 for background were assigned.
4. 'X' dataset is created with shape (500,28,28) and y dataset with shape (500,1).
5. X and y are saved in a npz file.  

### Evaluation using CNN:
1. Create X_train, X_test, y_train, y_test 
2. Add a new axis for X_train and X_test to provide channel information for CNN
3. CNN model is created and best model is saved.
4. Training and validation accuracy plot is implemented to check for underfit or overfit condition.

### Performance Chart 

![alt text](https://github.com/anurooprtj/iris-analysis/blob/master/performance_chart.png)


