#This study, hence, aims to identify risk factors and predict food security status at household level in North West Ethiopia using supervised machine learning techniques.
In 2018, more than 821 million undernourished people were registered all over the world. Of these, 239 million were in Sub-Saharan Africa. The numbers are particularly high in Ethiopia, Kenya, Somalia, and South Sudan. The determinant factors of food insecurity in Ethiopia are multidimensional encompassing climate change, civil conflicts, natural disasters, and social norms. To this end, a dataset was gathered from the Dabat Health and Demographic Surveillance and statistically interesting risk factors were identified using logistics regression at a threshold level of p<0.05. Three experiments were also conducted using random forest, support vector machine and decision tree (C4.5) to predict food security status at household level and the performance of each model was evaluated using accuracy, precision, recall, and f1- measure. As a result, the C4.5 algorithm is selected as the best appropriate supervised machine learning algorithm with 97.23% of recall, 91.58% of accuracy, 80.97% of f1-measure, and 69.38% of precision. Family size, level of education, age of the household head, number and types of communication media, numbers of livestock, cultivated land size, access to credit, and access to irrigation are some of the risk factors of food security.

Data Source :Dabat Research Center which is established by University of Gondar.

The dataset contains information about sociodemographic(family status) , location of head(location_info), Food secuirty related data(part_5) and Infrastructure facility(part3 and 4).

These five datasets (found in csv_data folder) have been integrated(familly_status_data,lab_part_4_grouped,labeled_part_3,labeled_part_5 and location_info).

Similarly the implementation for each dataset avalaible here (familly.ipynb,location.ipynb,part_3&4 and part_5.ipynb).


These datasets have been processed separatly and avalible in ( csv folder) and merged into one dataset using Final01.ipynb.

Risk Factors generated from filename "dummy-all.ipynb".


Relevant rules generated from file name "nominal-all_final best selected model.ipynb".



  Authors: 
  Melaku Alelign Mengstie
  https://www.linkedin.com/in/melaku-alelign-b1b034197/
  Tesfamariam M. Abuhay
  https://www.linkedin.com/in/tesfamariam-mulugeta-abuhay-b96a7161/
