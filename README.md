# hs_codes_prediction

## A semi-supervised training approach for predicting HS6 code for a product description

The current model is a MiniLM model trained using siamese triplet approach with cosine triplet loss. The model has top_5_hit accuracy of 83.3%.

### How to use the repository:
1. Create Triplets from HS codes datasets using _mining_triplets_ notebook
2. Train the model using _semi_supervised_training_ notebook
3. Vectorize and search utlities are available in _vectorize_n_search_ notebook
4. Models have been tested in _evalaution notebook_ for top_5_hit_accuracy.


