# Movie Recommender Systems
 
Implementation and evaluation of three recommender system algorithms on the **MovieLens 1M** dataset, using 5-fold cross-validation and RMSE/MAE metrics.
 
## Files
 
```
├── recommender_systems_group40.ipynb   # Main notebook — all three algorithms
├── visualizations_group40.ipynb        # Result plots and analysis
├── ratings.dat                         # 1M ratings (UserID::MovieID::Rating::Timestamp)
├── movies.dat                          # ~3,900 movies (MovieID::Title::Genres)
├── users.dat                           # 6,040 users (UserID::Gender::Age::Occupation::Zip)
├── users_mf.csv                        # Learned user latent factors (matrix factorization)
└── movies_mf.csv                       # Learned movie latent factors (matrix factorization)
```
 
## Dataset
 
[MovieLens 1M](https://grouplens.org/datasets/movielens/1m/) — 1,000,209 ratings by 6,040 users on ~3,900 movies. Download and place the `.dat` files in the project root before running the notebooks.
 
## Requirements
 
```bash
pip install pandas numpy scikit-learn matplotlib seaborn tqdm chardet
```
