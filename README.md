# Biometric Signature of Emotion: Multivariate Statistics
#### Tiago Almeida Cruz  | Master's Degree in Biomedical Engineering 
#
## Repository Organization: 
### Results and Discussion: 
#### &#8594; VAS-Pre questionnaire: 
* __Complementary Information A:__<br>Boxplots made for the cases where VAS-POS questionnaires were used, carried out after each emotional stimulation (Fear, Happy and Neutral). This information complements Section 5.1.2. 
>     A - Vas-Pos fear 
>Set of 5 figures, each one with 4 graphics. Each graph contains 3 Boxplots (1 per group of participants), that allows a comparison of the percentages (% of anxiety, happy, fear or stress) obtained in the VAS-Pos questionnaire (Session 1) made after fear stimulation, according to the groupings of participants made based on the cluster analysis on the features retained from the EMG, ECG, EDA, STICSA-State questionnaire or STICSA-Trait questionnaire (Session 1). 

>     A - Vas-Pos happy
>Set of 5 figures, each one with 4 graphics. Each graph contains 3 Boxplots (1 per group of participants), that allows a comparison of the percentages (% of anxiety, happy, fear or stress) obtained in the VAS-Pos questionnaire (Session 1) made after happy stimulation, according to the groupings of participants made based on the cluster analysis on the features retained from the EMG, ECG, EDA, STICSA-State questionnaire or STICSA-Trait questionnaire (Session 1). 

>     A - Vas-Pos neutral
>Set of 5 figures, each one with 4 graphics. Each graph contains 3 Boxplots (1 per group of participants), that allows a comparison of the percentages (% of anxiety, happy, fear or stress) obtained in the VAS-Pos questionnaire (Session 1) made after neutral stimulation, according to the groupings of participants made based on the cluster analysis on the features retained from the EMG, ECG, EDA, STICSA-State questionnaire or STICSA-Trait questionnaire (Session 1). 

* __Complementary Information B:__<br>Tables that shows the results of Kruskal-wallis test, One Way ANOVA or Welch's ANOVA, for the case in 
which the VAS-Pos questionnaires are used. This information complements Section 5.1.2. 
>     B - Vas-Pos fear 
>Table with the results of the statistical tests performed on the grouped values of the features anxiety, fear, 
stress and happy obtained in the VAS-Pos questionnaire made after fear stimulation, in order to verify the existence or not of significant 
differences between the groups formed based on the ECG, EDA, EMG signals (collected during fear stimulation), the state 
questionnaire, and the trait questionnaire.

>     B - Vas-Pos happy
>Table with the results of the statistical tests performed on the grouped values of the features anxiety, fear, 
stress and happy obtained in the VAS-Pos questionnaire made after happy stimulation, in order to verify the existence or not of significant 
differences between the groups formed based on the ECG, EDA, EMG signals (collected during happy stimulation), the state 
questionnaire, and the trait questionnaire.

>     B - Vas-Pos neutral
>Table with the results of the statistical tests performed on the grouped values of the features anxiety, fear, 
stress and happy obtained in the VAS-Pos questionnaire made after neutral stimulation, in order to verify the existence or not of significant 
differences between the groups formed based on the ECG, EDA, EMG signals (collected during neutral stimulation), the state 
questionnaire, and the trait questionnaire.

#### &#8594;  Feature Selection Results: 
* __Complementary Information C:__<br>Tables that show the features selected after implementation of the methodology A and after the methodology C (approach C1 and approach C2). This information complements Section 5.3. 

#### &#8594;  Principal Component Analysis Results: 
* __Complementary Information D:__<br>Graphs that shows features contributions to PC1. This information complements Section 5.4. 
>     D - Contributions PC1 - Fear
>Graphs that shows features contributions to PC1, obtained from the principal component analysis on the features, of the individuals belonging to group 1, 2, 3, or global, selected from methology A on the ECG, EDA, EMG, or ECG+EDA+EMG signals associated with fear stimuli.

>     D - Contributions PC1 - Happy
>Graphs that shows features contributions to PC1, obtained from the principal component analysis on the features, of the individuals belonging to group 1, 2, 3, or global, selected from methology A on the ECG, EDA, EMG, or ECG+EDA+EMG signals associated with happy stimuli.

>     D - Contributions PC1 - Neutral
>Graphs that shows features contributions to PC1, obtained from the principal component analysis on the features, of the individuals belonging to group 1, 2, 3, or global, selected from methology A on the ECG, EDA, EMG, or ECG+EDA+EMG signals associated with neutral stimuli.

>     D - Contributions PC1 - Baseline
>Graphs that shows features contributions to PC1, obtained from the principal component analysis on the features, of the individuals belonging to group 1, 2, 3, or global, selected from methology A on the ECG, EDA, EMG, or ECG+EDA+EMG signals associated with baseline.

* __Complementary Information E:__<br>Scatterplots matrix. This information complements Section 5.4. 
>     E - scatterplot matrix - Fear
>Scatterplots matrix considering the first three principal components obtained based on the 
principal components analysis over the features selected based on methodology A and with the 
consideration of ECG, EDA, EMG, or ECG+EDA+EMG signals on the emotional state of fear.

>     E - scatterplot matrix - Happy
>Scatterplots matrix considering the first three principal components obtained based on the 
principal components analysis over the features selected based on methodology A and with the 
consideration of ECG, EDA, EMG, or ECG+EDA+EMG signals on the emotional state of happy.

>     E - scatterplot matrix - Neutral
>Scatterplots matrix considering the first three principal components obtained based on the 
principal components analysis over the features selected based on methodology A and with the 
consideration of ECG, EDA, EMG, or ECG+EDA+EMG signals on the emotional state of neutral.

>     E - scatterplot matrix - Baseline
>Scatterplots matrix considering the first three principal components obtained based on the 
principal components analysis over the features selected based on methodology A and with the 
consideration of ECG, EDA, EMG, or ECG+EDA+EMG signals on the baseline.

#### &#8594; Final optimized model: 
* __Complementary Information F:__<br>Graphs of the results obtained With the optimized constructed model in terms of Recall and Precision. This information complements Section 5.5.1. 
