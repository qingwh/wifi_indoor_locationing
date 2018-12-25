# wifi_indoor_locationing
To investigate the feasibility of using "Wi-Fi fingerprinting" to determine a person's location in indoor spaces, I implemented random forest, KNN, and neural network to develop indoor positioning system by using WLAN/Wi-Fi fingerprint in Python (scikit-learn, Keras). I obtained outstanding results compared to Baseline Results of The 2015 EvAAL-ETRI Competition reported in literature.

Location of data sources: The data for this project is currently stored on a database consisting of 19937 training/reference records (trainingData.csv file) and 1111 validation/test records (validationData.csv file). The database is stored by the host which address is https://archive.ics.uci.edu/ml/datasets/ujiindoorloc

Reference: 
Joaquín Torres-Sospedra, Adriano Moreira, Stefan Knauth, Rafael Berkvens, Raul Montoliu, Oscar Belmonte, Sergio Trilles, Maria João Nicolau, Filipe Meneses, António Costa, Athanasios Koukofikis, Maarten Weyn and Herbert Peremans. A Realistic Evaluation of Indoor Positioning Systems Based on Wi-Fi Fingerprinting: The 2015 EvAAL-ETRI Competition. Article in Journal of Ambient Intelligence and Smart Environments Vol.9(2):263-279, February 2017. 
