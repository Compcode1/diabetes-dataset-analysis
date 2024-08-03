# diabetes-dataset-analysis
This project was halted after initial review of the dataset. 

The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. Each year, the survey collects responses from over 400,000 Americans on health-related risk behaviors, chronic health conditions, and the use of preventative services. It has been conducted every year since 1984. For this project, a csv of the dataset available on Kaggle for the year 2015 was used. This original dataset contains responses from 441,455 individuals and has 330 features. These features are either questions directly asked of participants, or calculated variables based on individual participant responses.

diabetes _ binary _ health _ indicators _ BRFSS2015.csv is a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes. This dataset has 21 feature variables and is not balanced.

My initial  reveals a significant deviation between the observed smoking percentages in this  dataset and the exopected national averages. Here are the key findings:

Observed Smoking Percentages:

Males (Smokers): 49.56%
Males (Non-Smokers): 50.44%
Females (Smokers): 40.19%
Females (Non-Smokers): 59.81%
Expected Smoking Percentages (Based on National Averages):

Males: 13.1%
Females: 10.1%
Deviation from Expected Values:

Males (Smokers): +278.34%
Males (Non-Smokers): +285.02%
Females (Smokers): +297.92%
Females (Non-Smokers): +492.18%

Implications of Deviation:

Smoking prevalence is a crucial factor in health outcomes, particularly concerning cardiovascular diseases, stroke, and respiratory conditions. The extreme deviation from expected smoking prevalence in this  dataset suggests several potential issues:

Sample Bias: The dataset may not be representative of the general population. It could be skewed towards populations with higher smoking rates, such as certain socioeconomic groups or regions.

Data Collection Method: The methodology used to collect data might have resulted in a non-representative sample.

Reporting Inaccuracies: There may be inconsistencies or errors in how smoking status was reported or recorded.

Impact on Dataset Validity
Given the significant role of smoking in determining health outcomes, understanding the cause of this deviation is critical. If the dataset is not representative, any analysis derived from it could be misleading. For instance, higher smoking rates could inflate the prevalence of related diseases like stroke and heart disease, leading to erroneous conclusions.

Without addressing the cause of the extreme deviation in smoking prevalence, the reliability of the entire dataset is compromised. It is essential to investigate further to determine whether the dataset can be adjusted to more accurately reflect the population or if a more representative dataset should be used.

If further documentation or information on the dataset is not available, considering an alternative dataset with known representativeness and accuracy would be advisable for any health outcome analysis.

