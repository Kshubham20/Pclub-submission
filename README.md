# Pclub-submission
**Task 1 criterions submission task submission **

At first I have generated the dataset using numpy for both the task.
1.In the file Linear Regression.ipynb I have have implemented the linear model using two loss functions seperately.
The comparison between the the results obtained by two loss function is given by
1.1 |X-x'|^3
    alpha = 0.1
    iters = 100
    theta = np.array([[1.0, 1.0]])
    Initial loss=142.41255233195704
    Final loss=6.85894655
    
1.2 |X-x'|
   alpha = 0.1
   iters = 100
   Initial weights = np.array([[1.0, 1.0]])
   Initial loss=142.41255233195704
   Final loss=3.70009208526238
   Final weights=[0.9        0.92059681]
   
   
2.In the file Linear Regression.ipynb I have have implemented the linear model using two loss functions seperately.
The comparison between the the results obtained by two loss function is given by
2.1|X-x'|^4
   alpha = 0.1
   iters = 2
   Initial weights = np.array([[1.0, 1.0,1.0]])
   Initial loss=159068.3736217764
   Final loss=6.184181658025238e+89
   Final weights=[-1.35746870e+19 -1.00249275e+20 -7.91122609e+20]
   
   
2.2 |X-X'|^7
  alpha = 0.1
  iters = 2
  Initial weights = np.array([[1.0, 1.0,1.0]])
   Inintial loss=8068884839.605289
   Final loss=5.33700774909547e+83
   weights=[-2.89844491e+08 -2.36087569e+09 -1.95819888e+10]
   
