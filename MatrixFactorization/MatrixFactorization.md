## Matrix Factorization Methods and Applications

[2013: 10701: Non-Negative Matrix Factorization](https://www.youtube.com/watch?v=UQGEB3Q5-fQ)<br>
[2018: How does Netflix recommend movies? Matrix Factorization](https://www.youtube.com/watch?v=ZspR5PZemcs)<br>
<br>
[2020: Art of the Problem: How Recommender Systems Work (Netflix/Amazon)](https://www.youtube.com/watch?v=n3RKsY2H-NE)<br>
    - collaborative filtering - use data to generate (latent) features, ie features are generated from data we have. Then make preds<br>
    - applications: Synthetic Control<br>
[MATRIX FACTORIZATION TECHNIQUES FOR RECOMMENDER SYSTEMS, Koren et al](https://www.inf.unibz.it/~ricci/ISR/papers/ieeecomputer.pdf)<br>

[GitHub: Collaborative Filtering with Neural Networks](https://github.com/yanneta/pytorch-tutorials/blob/master/collaborative-filtering-nn.ipynb)<br>
[FastAI: appl of PCA to movie recom](https://github.com/ftk1000/fastai/blob/master/nbs/46_tutorial.collab.ipynb)<br>
[]()<br>
[2019: Jill Cates YTvideo: How to Design and Build a Recommendation System Pipeline in Python (Jill Cates)](https://www.youtube.com/watch?v=v_mONWiFv0k)
- collaborative filtering (CF) - user-item (sparse) matrix scipy.sparse.csr_matrix; CF does not perform well with sparse matrix 
- content based filtering: looks at contect of users (age, gender, spoken lang) and movies (genre, cast, yr or release)
- PIPELINE: 1/ pre-processing, 2/ HP tuning, 3/ Model Train & Pred, 4/ Post_proc, 5/ Evaluation 
- Matrix Factorization algos: 
    - alternating least squares (ALS) 
    - stochastic gradient descent (SGD) 
    - singular value decomposition (SVD) 
- HP Tuning: sklearn.model_selection.GridSearchCV(), sklearn.model_selection.RandomizedSearchCV(), 
- HP Tuning: Sequential Model Based optimization: scikit-optimize (skopt); hyperopt; or Metric Optimization Engine (MOE)
- Eval of RecomSyst is done by masking some of the choices users made, as if we don't know them (see 18:45)
- Eval Metrics: precision =TP/(TP+FP) minimizes FP,   recall = TP/(TP+FN) minimizes FN
- Py Tools: 
    - import surprise (NikolasHug)
    - import implicit (benfred)
    - import lightFM (@lyst)
    - import pyspark.mlib.recommendation
        
[2009: Jill Cates blogpost: How to Build a Recommender Pipeine for Medical Research Papers](https://topspinj.github.io/recommender-pipeline/)<br>
[benfred's IMPLICIT: Fast Python Collaborative Filtering for Implicit Datasets.](https://github.com/benfred/implicit)<br>
[Finding Similar Music using Matrix Factorization  www.benfrederickson.com/matrix-factorization/](https://www.benfrederickson.com/matrix-factorization/)<br>
[2009 RENDLE ET AL: BPR: Bayesian Personalized Ranking from Implicit Feedback](https://arxiv.org/pdf/1205.2618.pdf)<br>
[]()<br>

# SVD
[SVD by Steve Brunton](https://www.youtube.com/watch?v=gXbThCXjZFM&list=PLMrJAkhIeNNSVjnsviglFoY2nXildDCcv&index=1)<br>
[]()<br>
[Least Squares Regression and the SVD](https://www.youtube.com/watch?v=02QCtHM1qb4&list=PLMrJAkhIeNNSVjnsviglFoY2nXildDCcv&index=14)<br>
[]()<br>
[]()<br>



## Text Classification

[SKLEARN: Out-of-core classification of text documents](https://scikit-learn.org/0.22/auto_examples/applications/plot_out_of_core_classification.html?highlight=datasets)<br>
[]()<br>
[]()<br>
[]()<br>
[]()<br>


## Probabilistic Graphical Models
[2017: Conditional Random Fields - Stanford University (By Daphne Koller)](https://www.youtube.com/watch?v=rc3YDj5GiVM&list=PLQl7D2xuMMNq5lj52YpCjGvgOrjvX4h5G)<br>
    - CRF generalized Logistic Regression Model<br>
[2017: Semantics & Factorization - Stanford University (Daphne Koller)](https://www.youtube.com/watch?v=1RgkCkN6IM0&list=PLQl7D2xuMMNq5lj52YpCjGvgOrjvX4h5G&index=4)<br>
    - Bayesian Ntwk Model (GAG) represents a joint prob distribution via the chain rule for CPD of the nodes $X_i$<br>
[]()<br>
[]()<br>
[]()<br>
[]()<br>


or create a new repository on the command line

    echo "# MatrixFactorization" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/ftk1000/MatrixFactorization.git
    git push -u origin master
                
…or push an existing repository from the command line

    git remote add origin https://github.com/ftk1000/MatrixFactorization.git
    git push -u origin master
