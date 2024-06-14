# Alzheimers-Disease-Detection
# Abstract
Alzheimer's disease (AD) is a neurological disorder that happens in the human 
brain. For Alzheimer's disease (AD), there is no specific treatment. Early detection of 
Alzheimer’s disease can help patients receive the correct care. Alzheimer's disease is a 
bit complex to analyze as far as indications as they cover numerous perspectives at the 
beginning phase. In the proposed methodology, MRI data is used to identify AD and 
deep learning techniques are used to classify the present disease. In this study, we have 
developed a system for Alzheimer’s disease detection using a convolutional neural 
network (CNN) architecture using magnetic resonance imaging (MRI) scan images that 
are trained using the Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset. The 
Dataset consists of four classes: Mild Demented, NonDemented, Very Mild Demented, 
Moderate Demented. Our CNN architecture comprises essential layers including 
Conv2D, MaxPooling2D, Flatten, Dropout, Fully Connected, and Softmax. Performance 
evaluation metrics such as Accuracy, Precision, Recall, and F1-score were employed. 
The model achieved an accuracy of 96.1%, showcasing its ability in Alzheimer's disease 
detection. 

# Data Base Description 
 Databases Description 
 A dataset is a collection of data. Most commonly a dataset corresponds to the 
contents of a single database table, or a single statistical data matrix, where every column 
of the table represents a particular variable, and each row corresponds to a given member 
of the dataset in question. The data set lists values for each of the variables such as the 
height or weight of an object for each member in the dataset. A data set is organized into 
some type of data structure. In a database, for example, a data set might contain a 
collection of business data (names, salaries, contact information, sales figures, and so 
forth). The database itself can be considered a data set, as can bodies of data within it 
related to a particular type of information, such as sales data for a particular corporate 
department. 
 
 The term data set originated with IBM, where its meaning was similar to that of 
file. In an IBM mainframe operating system, a data set is a named collection of data that 
contains individual data units organized (formatted) in a specific, ibm- ibm-prescribed 
way and accessed by a specific access method based on the data set organization. Types of 
data set organizations include sequential, relative sequential, indexed sequential, and 
partitioned. Access methods include the virtual sequential access method (VSAM) and the 
indexed sequential access method (ISAM). 
The dataset consists of two files - Training and Testing both containing a total of around 
~5000 images each segregated into the severity of Alzheimer's Classes: 
1. MildDemented 
2. VeryMildDemented 
3. NonDemented 
4. ModerateDemeneted
# Proposed model
The proposed model consists of MRI images in JPEG format, these images are 
preprocessed and deep learning features are implemented for the classification of 
Alzheimer's disease. The methodology is a hierarchy starting from the data collection. 
Here the data is collected from the open-source Kaggle website then the collected samples 
are preprocessed followed by CNN architecture that is used for feature extraction as well 
as classification of Alzheimer’s disease. Finally, the results are analyzed using 
performance metrics such as Accuracy, Precision, Recall, and F1 score. 

# Results 
 The results of our study showcase the potential of utilizing convolutional neural 
network (CNN) architectures for the early detection and classification of Alzheimer's 
disease (AD) from magnetic resonance imaging (MRI) scans. The high accuracy, 
precision, recall, and F1-score achieved by our proposed system underscore its 
effectiveness in discriminating between different classes of AD severity, including mild 
demented, moderate demented, non-demented, and very mild demented. These findings 
are particularly encouraging considering the challenges associated with early diagnosis 
and intervention in AD, where timely detection is critical for initiating appropriate care 
strategies. By leveraging deep learning techniques and neuroimaging data, our system 
offers a promising avenue for enhancing diagnostic accuracy and facilitating personalized 
treatment plans for individuals at risk of AD. Furthermore, the robust performance of our 
model in predicting AD classes highlights its potential utility in clinical settings, where 
accurate and efficient disease classification is paramount. Moving forward, continued 
research efforts are warranted to further refine and validate our proposed system, 
including the exploration of larger and more diverse datasets, the integration of 
multimodal imaging modalities, and the development of interpretable deep learning 
architectures to enhance clinical decision-making and patient care.
