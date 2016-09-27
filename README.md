# Lifelog Dataset (v1.0)
## Main Reference
- "Dual Memory Neural Networks for Modeling Cognitive Activities of Humans via Wearable Sensors", S.-W. Lee, C.-Y. Lee, D.-H. Kwak, J.-W. Ha, J. Kim, and B.-T. Zhang, submitted to Neural Network Journal.


## Description
<img src="Lifeome.png" width="500"  />

This dataset collect human life's activity data through Google Glass over 46 days from three participants.

| Participant   | Training     | Test        | Location | Sub-location | Activity |
| :---      |  ---: |  ---: |  ---: |  ---: | ---: |
| A  | 105201 (13)  | 17055 (5)   | 18  | 31 |  39 |
| B  | 242845 (10)  | 91316 (4)   | 18  | 28 |  30 |
| C  | 144162 (10)  | 61029 (4)   | 10  | 24 |  65 | 
```
The elements of training and test denote the length of instances (sec/day).  
The elements of Location, Sub-location, and Activity denote the number of behavior.
```
For each image instance, location, sub-location, and activity is notated.

## Data download link
- Participant A [[image feature](AlexNet_A.hdf5)] [[class](class_A.hdf5)] [[classinfo](classinfo_A.hdf5)]
- Participant B [[image feature](AlexNet_B.hdf5)] [[class](class_B.hdf5)] [[classinfo](classinfo_B.hdf5)]
- Participant C [[image feature](AlexNet_C.hdf5)] [[class](class_C.hdf5)] [[classinfo](classinfo_C.hdf5)]
