# Performance versus privacy in IoT-based device security using federated learning

This GitHub repo contains the supporting notebooks for the "Performance versus privacy in IoT-based device security using federated learning" by Jonathan White and Phil Legg.

The paper experiments on the CICIoT2023 dataset and explores machine learning performance under various distributions of the data across a set of federated clients. Specifically we examine whether a comparable model can be developed using a federated learning approach as opposed to a centralised approach. We also examine the impact of the number of clients and the distribution of the data across the clients on the performance of the model.

The notebooks are as follows:

- `01-Data_Exploration.ipynb` - This notebook explores the CICIoT2023 dataset and provides some context of the data.
- `02CICIoT2023-MLclassifier.ipynb` - This notebook trains machine learning classifiers on the CICIoT2023 dataset using a centralised approach to replicate the original author's work, using the corrected, full training dataset.
- `03-Federated_Learning.ipynb` - This notebook trains machine learning classifiers on the CICIoT2023 dataset using a federated learning approach. The notebook also explores the impact of the number of clients and the distribution of the data across the clients on the performance of the model. Using the defines at the top of the notebook, the various data distribution scenarios and classification problem can be selected.

Due to the size of the dataset, it is not included in this repo. The dataset can be downloaded from the CICIoT website (see below). The dataset should be downloaded and extracted into the `data` folder. It is suggested that these notebooks are run on a machine with a minimum of 64GB of RAM.

CICIoT Paper:   [CICIoT2023: A Real-Time Dataset and Benchmark for Large-Scale Attacks in IoT Environment](https://www.preprints.org/manuscript/202305.0443/v1)

CICIoT Dataset: [CIC IoT Dataset 2023](https://www.unb.ca/cic/datasets/iotdataset-2023.html)

