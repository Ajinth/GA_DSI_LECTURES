# Feature Selection and Grid Search

By the end of this lesson, you should be able to:

- Feature Selection
    1. Identify common techniques to help select features for models
    2. Define bottom-up and top-down feature selection and apply one sklearn object for each:
      - Bottom-up: [Recursive Feature Elimination](http://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFE.html)
      - Top-down: [SelectKBest](http://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.SelectKBest.html#sklearn.feature_selection.SelectKBest)
- Grid Search (Hyperparameter optimization)
    1. Define a hyperparameter and identify common hyperparameters for the following machine learning techniques:
      - Regression Techniques
        - [Linear Regression](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
        - Regularized Linear Regression ([Lasso](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html#sklearn.linear_model.Lasso), [Ridge](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html#sklearn.linear_model.Ridge), [ElasticNet](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.ElasticNet.html#sklearn.linear_model.ElasticNet))
      - Classification Techniques
        - [Logistic Regression and Regularized Logistic Regression (Lasso, Ridge)](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html#sklearn.linear_model.LogisticRegression)
        - [_K_-Nearest Neighbors](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
    2. Define what grid searching conceptually and how it is used in the modeling process
    3. Apply the [`GridSearchCV`](http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html) object during modeling

Due to the heavy coding portion of this lesson, we will work through the [feature_selection_and_grid_search.ipynb](./feature_selection_and_grid_search.ipynb) Jupyter Notebook together.