# ICU-Mortality-Prediction
A patient survival prediction model leveraging machine learning techniques and data from the first 24 hours of intensive care.

## Abstract
Intensive Care Units in hospitals are one of the most critical places. A patient is moved to the ICU when their health is deteriorating. The urgency and type of therapy are determined by examining the patient. We can respond to threats ahead of time and offer the patient more advanced care if we can estimate a patient’s survival probability using data from multiple metrics collected during the first 24 hours of admission to an intensive care unit. This increases the patient’s chances of survival. As a result, the mortality rate in hospitals will be lower. A critical point to remember in this case, as in many others, is that the data is highly skewed. The goal is to develop a model that predicts patient survival based on data from the first 24 hours of intensive care.

## Dataset

The dataset has been released as open source by MIT
GOSSIS community initiative, with privacy certification from
the Harvard Privacy Lab. The dataset consists of more than
130,000 hospital Intensive Care Unit (ICU) visits from patients, spanning a one-year timeframe at various hospitals
located in Argentina, Australia, New Zealand, Sri Lanka,
Brazil, and more than 200 hospitals in the United States. The
dataset consists of 186 attributes and 91713 instances – out
of which 15 are categorical and 171 are of numerical type.
The target attribute we are trying to predict is ‘hospital death’
– 1 implies death and 0 implies survival. Out of the 91713
instances in our dataset - 83798 entries correspond to a survival
7915 entries correspond to a death. As we can see, the dataset
is skewed and this is addressed in the following sections.
