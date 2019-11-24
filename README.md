# CLASSIFIER
  - pure python based implementation of classifier which can be used as an binary image classifier or yes/no classifier 
  - almost no use of external libraries except numpy
  - comes with generated trained files
  ### REQUIREMENTS
      - scikit-learn (*only for the loading of the MNIST dataset*)
      - numpy -> mainly used to simplify most of the mathematical operations
      - pandas -> used to load the dataset and a little bit of preprocessing
      - matplotlib -> not mandatory, but used for visualisation purposes

## ABOUT
  - the classifier can answer a question generated by a given dataset
  - it works well with given MNIST dataset or csv files
  - the learning rate and the epoches of the gradient descent is somewhat random values and might be not the optimal ones
  - a part of the data processing is done based on the sample dataset in the repo, feel free to adjust the processing pipeline     according to your data 
  - if you want new training weights, feel free to delete the training files, adjust the part of the code you need and the         program will generate new metafile based on your settings    
  - the classifier contains a lot of redundant code, many of the things can be optimized but still produces correct result in a     reasonable amount of time
  
  ### DEMO
    - Image classifier
       - Actual ![Image description](will edit later)
       - Predicted ![Image description](will edit later)
       
    - Normal classifier
        - ![Image description](https://github.com/VenkoChakalov/classifier/blob/master/demo/1.png)
    
