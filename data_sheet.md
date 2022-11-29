# Datasheet

## Motivation

- For what purpose was the dataset created? 
    - Answer: the dataset was created to predict based on diagnostic measurements whether a patient has diabetes.
- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?

(a) Original owners: National Institute of Diabetes and Digestive and
Kidney Diseases
(b) Donor of database: Vincent Sigillito (vgs@aplcen.apl.jhu.edu)
Research Center, RMI Group Leader
Applied Physics Laboratory
The Johns Hopkins University

 
## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 
    - people
- How many instances of each type are there? 
    - 768
- Is there any missing data?
    - yes
- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by    doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?
    - yes, but there is no identifier in the data hence it's not possible to tie back to an individual.

## Collection process

- How was the data acquired? 
    - it was selected from a larger database. The data was originally from the National Institute of Diabetes and Digestive and Kidney Diseases.
- If the data is a sample of a larger subset, what was the sampling strategy? 
    - it was sampled according to some constraints:all patients here are females at least 21 years old of Pima Indian heritage
- Over what time frame was the data collected?
    - didn't have this information

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 
    - No
- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 
 
## Uses

- What other tasks could the dataset be used for? 
    - It's mainly used to predict whether a patient has diabetes.
- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 
    - yes. Refer to the Collection process for the data collection criteria.
- Are there tasks for which the dataset should not be used? If so, please provide a description.
    - probably shouldn't be used for harmful purposes.

## Distribution

- How has the dataset already been distributed? 
    - it's published on Kaggle: https://www.kaggle.com/datasets/mathchi/diabetes-data-set?resource=download
- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?  
    - No. It's published under CC0: Public Domain Licence.

## Maintenance

- Who maintains the dataset?
    - Vincent Sigillito (vgs@aplcen.apl.jhu.edu) Research Center, RMI Group Leader Applied Physics Laboratory The Johns Hopkins University Johns Hopkins Road Laurel, MD 20707 (301) 953-6231
