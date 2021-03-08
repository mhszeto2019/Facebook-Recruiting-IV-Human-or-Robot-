# Facebook-Recruiting-IV-Human-or-Robot-

This is my first attempt in a Kaggle Competition.
Goal of this competition:
-Gaining experience with large datasets
-Practise "cleaning"  of data.
-Learning how to use different Machine Learning Models

Link to competition: https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/data

**Features used in this model:** 
['auction', 'merchandise', 'device', 'country', 'ip', 'url', 'num_bids', 'maxtime_num', 'mintime_num', 'maxdiff_num', 'mindiff_num', 'meandiff_num', 'mediandiff_num', 'mean_entropy', 'median_entropy', 'std_entropy', 'median_ips_per_bidder_per_auction', 'mean_ips_per_bidder_per_auction', 'std_ips_per_bidder_per_auction', 'ip_entropy', 'median_country_per_bidder_per_auction', 'mean_country_per_bidder_per_auction', 'std_country_per_bidder_per_auction', 'country_entropy', 'median_devices_per_bidder_per_auction', 'mean_devices_per_bidder_per_auction', 'std_devices_per_bidder_per_auction', 'device_entropy', 'bids_per_auction', 'bids_per_url', 'bids_per_ip', 'bids_per_country', 'mean_country_per_auction', 'max_country_per_auction', 'min_country_per_auction', 'std_country_per_auction', 'mean_devices_per_auction', 'max_devices_per_auction', 'min_devices_per_auction', 'std_devices_per_auction', 'mean_ip_per_auction', 'max_ip_per_auction', 'min_ip_per_auction', 'std_ip_per_auction', 'check_first', 'check_last']

**Models and parameters used: **
1)RandomForestClassifier(n_estimators=160, max_features=35, max_depth=8, random_state=20, criterion='entropy',) xgb.XGBClassifier(objective= 'binary:logistic', nthread= 10, eval_metric= 'auc', silent= 1, seed= 20, max_depth= 6, gamma= 0, base_score= 0.50,min_child_weight= 4, subsample= 0.5,colsample_bytree= 1, eta= 0.01,)
2)CatBoostClassifier(random_seed=20)
