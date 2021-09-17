# Solution is divided into 4 parts:
- Preprocessing
- Find best Encoders
- Find best features
- Stacking classifiers and make prediction

1. **Preprocessing**:
- fill nan values.
- create new features.

2. **Find best Encoders**:
- tried different encoders and their combination for categorical features
- best encoder criteria (best average score CV score + validation pred score for different classifiers)

3. **Find best features**:
- create lot of combination of features
- try different combination of features, make prediction and select features with best CV score prediction

4. **Stacking Classifiers and make prediction**:

- stacking different classfiers
- make prediction

### Final Score top 4.5% (17/09/2021): 
![alt text](https://github.com/gurokeretcha/Top-5-Kaggle-titanic-disaster-solution-/blob/main/images/Screenshot%202021-09-17%20232228.png)



