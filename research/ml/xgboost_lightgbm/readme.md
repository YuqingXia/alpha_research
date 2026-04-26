# Context

When do feature engineering, linear regression and classification although is good but typically harder to explore nonlinear and interaction features, which typically is crutial in finance word. Most of problem is not exactly linear or independent. So I feel xgboost and lightgbm such method can be used for initial step feature exploring, which can give us a light which direction we should explore to get promising results. For example, some signal like bond auction which has different trading direction before and after 1pm (auction time). The time cut initially is hard to find unless you define explicitly, especially the trending direction typically switch before and after. so that means there is an interaction between trending direction before and after 1pm. 

