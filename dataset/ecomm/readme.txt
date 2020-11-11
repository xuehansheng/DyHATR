This network data is sampled from ：https://tianchi.aliyun.com/competition/entrance/231719/information
deliminator: '\t'
Snapshot time step: 1 day,
Total snapshots: 11
The first 10 snapshots are used for training, the last snapshot is used for validation and evaluation.


ecomm_edge_train.txt:
1st col: user id
2nd col: item id
3rd col: edge type, 1: clk; 2: collect; 3: cart; 4: buy
4th col: date

ecomm_edge_val_lr_train_test.txt:
Validation set and Link Prediction task training and test set.
1st col: node id.
2nd col: node id.
3nd col: edge label. 1 for positive, 0 for negative.
4nd col: data split label. 0 for validation set, 1 for link prediction training set, 2 for link prediction test set.

ecomm_graphsage_walk_pairs_dynamic.txt:
The random walk node pairs based on the last snapshot.
1st col: node id.
2nd col: node id.

ecomm_item_feature.txt:
1st col: item_id
2nd col: cate_1_id
3rd col: cate_id
4th col: brand_id
5th col: price

ecomm_user_feature.txt:
1st col: user_id
2nd col: pred_gender, 1 or 0.
3rd col: pred_age_level, [0-9]
4th col: pred_education_degree, [1, 2, 3, 4, 5]
5th col: pred_career_type, [1-10]
6th col: predict_income
7th col: pred_stage, [1-10]
