# Monoshiz_20newsgroup

0. Data is [20 newsgroup](https://www.kaggle.com/crawford/20-newsgroups)
1. Task
    Data -> training (10 newsgroups) + test (rest)
    
    Training: you can do whatever you want on your training data.
    Test:
     - 1 target class (which is not in training), 1 example of this target class.
     - cost: you can query about the label of any data point in the test data, but it will have a cost of 1.
     - find as many target class data in test data as possible with least cost. Max recall min cost.
    
