# SPAND_Dataset
Anonymized dataset containing fetaure data and graph data extracted from mobile data (SNAPSHOT Study). 

Maryam Khalid, Elizabeth B. Klerman, Andrew W. McHill, Andrew J. K. Phillips, and Akane Sano. 2024. SleepNet: Attention-Enhanced Robust Sleep Prediction using Dynamic Social Networks. Proc. ACM Interact. Mob. Wearable Ubiquitous Technol. 8, 1, Article 37 (March 2024), 34 pages. https://doi.org/10.1145/3643508

To protect study participants' privacy and consent and since some of the participants did not consent to sharing their data with the third-party researchers, data has been deidentified. Furthermore, data has been transformed in a way that an individual participant's data can not be identified. This process can be reversed and data can be used to reproduce to the results presented in this work or for developing new machine learning solutions through standardization of data. Please refer to the standardization process reported in the paper.

The file 'feature.csv' contains anonymized user ID in first column, followed by anonymized timestamp. The timestamp is anonymized but the sequence is preserved i.e difference between timestamps when samples were collected is preserved. The third column 'time_in_bed' contains the sleep label.

The Graph data is contained two pickle files. Call_graph.pkl and Sms_graph.pkl contain the graphs extracted from call and sms metadata.
