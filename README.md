

Brain Tumor Classification


authors: Katerina Vilkomir, Jerrica Deloatch, Tara Gill


*Introduction*

Our DNA gives instructions to our cells. Sometimes DNA mutates and instructs cells to duplicate abnormally, forming a tumor. A mass of abnormal brain cells is referred to as a brain tumor. Brain tumors can be of many various sorts, including Gliomas, Meningiomas, Pituitary, etc. Brain tumors can be primary, meaning it originates in the brain itself, or secondary, meaning it is caused by cancer spreading to the brain from a different part of the body. While some brain tumors are benign (noncancerous), others are malignant (cancerous). This means that while all brain malignancies are tumors, not all brain tumors are malignant. Given that brain tumors can be fatal and brain cancer has a low survival rate, early diagnosis is crucial. Early detection is also important in non-fatal outcomes, as brain tumors can form in regions of the brain that regulate cognitive and motor functions, making rehabilitation a necessary part of recovery.

*Findings*

The authors of The association between incidence and mortality of brain cancer and human development index (HDI): an ecological study, Zaher Khazaei et al., write, “According to the results of Global Cancer Registry in 2018, there were 29,681 registered cases of brain related cancer”. Yang Fan, et al., authors of Burden and trends of brain and central nervous system cancer from 1990 to 2019 at the global, regional, and country levels report, “In 2019, there were approximately 347,992 global cases of brain and CNS cancers, which showed a significant increase (94.35 percents) from the period between 1990 to 2019.”

*Problem*

Brain tumor diagnosis is time-consuming and strongly dependent on the skills and expertise of the radiologist. In underdeveloped areas, there may be a lack of neurosurgeons who can skillfully interpret MRI results. And in moderately staffed areas, an increase in the number of patients has caused outdated practices to be both expensive and inefficient.

*Proposed Approach*

Machine learning approaches address these problems. For this project, we would like to train a discriminative model to distinguish between tumor and normal tissues. To do so, we have collected datasets from Kaggle, which we prepare by cleaning, randomizing, and splitting. After our data is prepared, we train and evaluate our model. With our first evaluation, we were able to tune the parameters in our model to increase its accuracy. We hope to continue to improve our model. If time permits, we would like to add a "Glioma" tumor, "Meningioma", "Pituitary" classification.

*References*

Fan, Yang, et al. "Burden and Trends of Brain and Central Nervous System Cancer from 1990 to 2019 at the Global, Regional, and Country Levels - Archives of Public Health." BioMed Central, BioMed Central, Sept 17, 2022, https://archpublichealth.biomedcentral.com/articles/10.1186/s13690-022-00965-5#:~:text=In%202019%2C%20there%20were%20347%2C992,%25%20%5B%2D27.27%E2%80%9332.83%5D. 


Johns Hopkins Medicine. (2023). Brain Tumors and Brain Cancer. Johns Hopkins Medicine. Retrieved February 6, 2023, from https://www.hopkinsmedicine.org/health/conditions-and-diseases/brain-tumor 

 
Khazaei, Zaher, et al. "The Association between Incidence and Mortality of Brain Cancer and Human Development Index (HDI): An Ecological Study." BMC Public Health, U.S. National Library of Medicine, Nov 12, 2020, https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7664078/. 

 
National Institutes of Health. (n.d.). Cancer of the brain and other nervous system - cancer stat facts. National Cancer Institute. Retrieved February 5, 2023, from https://seer.cancer.gov/statfacts/html/brain.html 

 
 
 

*Sources for brain_archive folder:*

1. https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection 
2. https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection  
3. https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset for no tumors  
4. https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri for no tumors 

*Sources for brain_archive_colorcheck folder:*

1. https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection 
2. https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection  
3. https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset for no tumors  
4. https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri for no tumors 
5. https://www.kaggle.com/datasets/leaderandpiller/brain-tumor-segmentation yes, no different colors and brightness

