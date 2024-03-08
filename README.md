# ossw2023

# OSSW 2023 Final Project
### 20221556 조민지

## Explain what you do in your project
Create an algorithm with **scikit-learn** to **predict brain tumor type** by training the given brain tumor image dataset.

## Explain the training dataset
Brain Tumors are classified as *Benign Tumor, Malignant Tumor, Pituitary Tumor, etc* and each folder contatins *MRI data* for each tumor classes. The images are split into Training and Testign folders.

## Explain the algorithm you choose
**Random Forest** is a type of ensemble learning, an algorithm that combines multiple decision trees to create prediction model with better performance. Each decision tree learns on a subset of data, the algorithm combines the result to make a more stable and high-performance model.

## Explain hyper-parameter of the function
I tuned as n_estimators=50, max_depth=15, class_weight='balanced'.
- n_estimators : The number of trees in the forest
- max_depth : The maximum depth of the tree
- class_weight : Weights associated with classes in the form ``{class_label: weight}``.

These are hyper-prameter of random forest.
>   n_estimators=100,
    criterion='gini',
    max_depth=None,
    min_samples_split=2,
    min_samples_leaf=1,
    min_weight_fraction_leaf=0.0,
    max_features='sqrt',
    max_leaf_nodes=None,
    min_impurity_decrease=0.0,
    bootstrap=True,
    oob_score=False,
    n_jobs=None,
    random_state=None,
    verbose=0,
    warm_start=False,
    class_weight=None,
    ccp_alpha=0.0,
    max_samples=None
