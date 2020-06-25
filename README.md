# Two_Level_Ensemble-classifier-chain
In this paper,we propose a novel two-layer prediction model for identifying AMP and its functional types, while using ADASYN oversampling technology to solve imbalance and multi-label problems.First, we encode the antibacterial peptides in three different feature representations, in order to effectively explore more informative feature sets. Then, we use Pseudo (PSE) and Discrete Wavelet Transform (DWT) to convert the variable length coding matrix into the equidimensional features. Also, we use model-based feature selection method for feature selection. Six individual feature sets (DWT-AAC, DWT-PSSM, DWT-PP, PSE-AAC, PSE-PSSM, PSE-PP) can be used to construct various base classifiers.Second,The first layer of the model is a binary classification problem, which is predicted using the bin\_ecc model.Third,We use ADASYN to oversample different functional types of AMP and then train a multi-label multi-class model.
![](https://github.com/kkzheng/Two_Level_Ensemble-classifier-chain/blob/master/flow.jpg)
