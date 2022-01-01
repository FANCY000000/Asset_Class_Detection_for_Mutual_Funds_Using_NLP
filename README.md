# Asset_Class_Detection_for_Mutual_Funds_Using_NLP

In some commonly-used websites such Fundata, the classification of a certain mutual fund is simply labeled as 'Equity' or 'Alternatives', which contradicts its asset allocation. While Bloomberg Terminal does have its classification for funds but the data is limited and we aim to generalized the techniques in a broader scope.

This project proposes to determine the accurate asset class of the fund based on its description. The project starts from scraping principal investment strategies of American mutual funds from US Securities and Exchange Commission (SEC). Afterward, we did some data cleaning and data exploration. Finally, We implement machine learning (Naive Bayesian, K-Nearest Neighbors, and Random Forest) and deep learning algorithms (LSTM and Bert) to train and predict the corresponding asset class, using the asset class provided by Bloomberg as a label.

Such fund classification could be further used to justify whether the existing blended benchmark is a good fit for a certain asset portfolio, or to find the optimal ratio of each blended benchmark component, thus helping our clients make better investment decisions.

Group members: Fangxin Wang, Wanru Hu, Yanru Chen and Sihan Yang
