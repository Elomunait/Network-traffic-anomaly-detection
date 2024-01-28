# Network Traffic Anomaly Detection using Neural Networks

## Overview

This repository contains code for building a neural network model for network traffic anomaly detection, specifically focused on intrusion detection. The model is developed at the intersection of NLP (Natural Language Processing) and Network Security, utilizing the Intrusion Detection Evaluation Dataset (ISCXIDS2012).

## Dataset

The dataset used for this project is the [Intrusion Detection Evaluation Dataset (ISCXIDS2012)](https://www.unb.ca/cic/datasets/ids.html), as introduced by Ali Shiravi, Hadi Shiravi, Mahbod Tavallaee, Ali A. Ghorbani in their paper "Toward developing a systematic approach to generate benchmark datasets for intrusion detection" (Computers & Security, Volume 31, Issue 3, May 2012).

## Prerequisites

Before running the code, ensure that you have the required dependencies installed. You can install them using the following commands:

```bash
pip install gensim
pip install python-Levenshtein
pip install tensorflow==2.4
```

## Usage

1. **Download the Dataset:**
   - Run `wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/Advanced_ML_anomaly_detection_L3/DataSets.zip` to download the dataset.

2. **Extract Dataset:**
   - Unzip the downloaded dataset, and specify the file number to use in the main code.

3. **Run the Code:**
   - Execute the provided code, filling in any placeholders (`##YOUR CODE GOES HERE##`) with your specific information.

4. **Model Training:**
   - The code will perform data preprocessing, build and train the neural network model, and visualize the results.

5. **Save and Load Model:**
   - Save the trained model using a chosen name (`M_name`), and load it back for predictions.

## Customization

- Adjust hyperparameters, such as `drop_level` and `N_neurons`, in the model-building section to experiment with different configurations.
- Explore different values for batch size, epochs, optimizer, and loss function during model compilation.

## Results

View the training history, including loss and accuracy metrics, to assess the performance of the trained model. Model predictions are also checked for further verification.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Original dataset: [ISCXIDS2012](https://www.unb.ca/cic/datasets/ids.html)
- References: Ali Shiravi, Hadi Shiravi, Mahbod Tavallaee, Ali A. Ghorbani, "Toward developing a systematic approach to generate benchmark datasets for intrusion detection," Computers & Security, Volume 31, Issue 3, May 2012.
- Sergii Kavun
