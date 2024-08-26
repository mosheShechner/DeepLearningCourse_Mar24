# Fighting Memorization: Training and Normalization effect in an MLP NN - A case study

This reposatory contains the code of final project of 'Deep Learning' Course by Prof. Lior Wolf and Dr. Idan Schwartz, Fall 2023.

The project follows up [NeurIPS'22 HVYSI] paper and the model inversion attack it presents. A model inversion is the process of reconstructing training data from a model parameters. We axamine several aspects of the presented attack and pose follow up research questions that arise from our observations. Project tests results are given in the course report along with cocluding discussion and follow up research questions.

The reposatory consist of two notebooks that were used to conduct the tests for the project:
1) Code of reproducing results of [NeurIPS'22 HVYSI]; Code of testing normalization effect:   Test_normalization_effect.ipynb
2) Code of testing training leangth effect; Code of testing 'kkt-loss' regularization:      Test_regularization_term_effect.ipynb

The notebooks imports code from [NeurIPS'22 HVYSI] project. To get this code see the repository linked in the paper.
[NeurIPS'22 HVYSI] - Reconstructing Training Data From Trained Neural Networks.
