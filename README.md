# BLEPNet
## In-Silico B-Cell Epitope Prediction Using Deep Learning
### Repository contains BLEPNet code and custom datasets in .zip file

BLEPNet: In-Silico B-Cell Epitope Prediction Using Deep Learning
Mihir Rao
Chatham High School

Supervised by: Dr. Yelena Naumova (Chatham High School)


Epidemiological control of a viral disease heavily depends on the production speed and efficacy of vaccines. At a molecular level, pathogens present antigen molecules that interact with B-lymphocyte antibodies at specific regions of the antigen molecule known as epitopes. B-cell epitopes are immunostimulants and computationally predicting them can significantly aid in the vaccine and therapeutic antibody development processes as an in-silico alternative to the time and resource-consuming in-vitro epitope-mapping efforts. However, existing approaches yield poorly performing prediction systems and are, thus, unreliable. In this work, a novel computational prediction system is developed and validated to address this problem. Quantitative analysis of a custom dataset reveals characteristics about antigens that can be used to improve existing in-vitro processes. In order to address the predictive nature of this problem, deep learning is implemented in order to classify k-mer peptide subsequences as immunostimulant or not. A bidirectional-LSTM architecture is implemented using 10-fold cross-validation. The resultant models are integrated as part of a novel B-cell epitope prediction system called BLEPNet (B-lymphocyte Epitope Prediction Network). As part of this system, biological insights that were acquired from the analysis of epitope data are used to enhance system performance. System evaluation indicated significantly superior predictive performance in comparison to existing computational approaches. The applicability of the resultant system is demonstrated through the usage of the developed web-interface to predict SARS-CoV-2 epitopes. This work is immediately applicable in the fields of vaccine development, drug and therapeutic design, and cancer immunotherapy development.



