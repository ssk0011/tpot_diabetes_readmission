# tpot_diabetes_readmission
Using TPOT AutoML package for determining best configured ML model for Diabetes Hospital Readmission data. Includes feature engineering, scaling and PCA.

## Motivation
Initial research in the field showed most ML models had not fared better than 70% aside from neural network implementations. This project was a test of newer packages in the auto machine learning field to see whether genetic programming-based testing could yield a better model plus higher accuracy

## Result
As of 8/13/23, the model of choice from TPOT (ExtraTreesClassifier) still only had roughly 63% accuracy. This implies either more research is required in neural network implementations (which was avoided due to limited hardware/GPU access at the time this project was started), or revised feature engineering work.

![image](https://github.com/ssk0011/tpot_diabetes_readmission/assets/16009336/6f08d306-9e4e-47f2-9889-a42eb122693d)


## Future Work
PCA heavily reduced the dimensionality of the feature space, but new features may need to be calculated from existing ones in order to increase the accuracy. Should access to a cluster be available in the future, it will be utilized for this project. Neural networks will be testing and tuned as well.
