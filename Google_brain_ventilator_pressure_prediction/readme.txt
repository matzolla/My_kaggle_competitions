The file is empty for now but i will be uploading step by step notebooks as the competition is in progress.
Up to november 04 2021
kaggle: ventilator-pressure-prediction challenge. 
-Discussion: since the expiratory phase is not scored, it's ok, we can do the cumulative sum of the u_in feature.
adding lag u_in as a new feature
adding last u_in as new feature 

- GroupKFold for time series, when using time series data , (shuffle=True) on train_test_split

- https://www.kaggle.com/jorijnsmit/found-the-holy-grail-grouptimeseriessplit 

- u_out does'nt have an impact apparently since it represents expiratory phase  which is not scored.

-https://www.kaggle.com/c/ventilator-pressure-prediction/discussion/274144 good discussion on some peaks

-interesting notebook https://www.kaggle.com/dmitryuarov/ventilator-pressure-eda-lstm-0-189

https://www.kaggle.com/kensit/improvement-base-on-tensor-bidirect-lstm-0-173
https://www.kaggle.com/usharengaraju/eda-fe-tabnet-weights-and-biases

The research paper is very insightful https://arxiv.org/pdf/2102.06779.pdf

https://www.kaggle.com/abhishek/always-splitting-data-first by abishek takhur


https://www.kaggle.com/marutama/eda-about-u-in


so far, this is my starter notebook ideas https://www.kaggle.com/cdeotte/ensemble-folds-with-median-0-153

Nomarly overparemetrized models will suffer from the variance-biased trade-off , but in this competition it seems as the model failed to overfit due to a possible interpolating regime which i don't know the origin. Here is the link to a paper explaining the phenomenon https://www.pnas.org/content/pnas/116/32/15849.full.pdf


Here is a very great link for almost all winning solutions of competitions https://www.kaggle.com/sudalairajkumar/winning-solutions-of-kaggle-competitions

C and R explained in this link https://www.kaggle.com/c/ventilator-pressure-prediction/discussion/276599

https://www.kaggle.com/snnclsr/a-dummy-approach-to-improve-your-score-postprocess?scriptVersionId=76215088

https://equatorial-jobaria-9ad.notion.site/Some-quick-notes-on-Google-Ventilation-Comp-9c63e233ec7b498d8b6e4f51dc0407f6
