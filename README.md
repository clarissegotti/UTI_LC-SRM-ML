### 4 scripts provided :

- *Inoculations_Quantification_Linear_Regressions_Pearson* allows to generate the calibration curves based on the 360 inoculations dataset (15 bacterial species x 6 concentrations x 4 replicates), as well as Pearson correlation

- *Inoculations_Reproducibility* allows the calculation of the RSD (%) at the analytical, technical and biological levels in the Reproducibility dataset (4 bacterial species, 2 backgrounds, 6 replicates)

- *Unknown_Samples_01_Discretization_for_ML* allows to discretize (TRUE/FALSE) the detected peptides based on Skyline transition exports, and could be used as an input for ML

- *Unknown_Samples_02_Quantification* allows the quantification of new samples based on the previously generated linar regressions


### Machine learning models :

From BioDiscML (https://github.com/mickaelleclercq/BioDiscML)
- bacteria_d.bayes.BayesNet__MCC_all.model, first generation model from high resolution DIA data
- all_d.trees.RandomForest_-I10-K0-S1_ACC_all.model, new random forst model from SRM data
