# Wi-Fi-CSI-based-HAR

Wi-Fi Channel State Information (CSI) Based Human Activity Recognition (HAR) involves using the fine-grained information about wireless channel conditions to detect and classify human activities.

# Introduction

This repository presents a privacy-preserving Human Activity Recognition (HAR) system using Wi-Fi Channel State Information (CSI) signals. Our approach leverages LSTM-based architecture to detect and classify activities such as 'idle', 'walking' and 'standing' with high accuracy, even in low-light scenarios. This non-vision-based method offers a secure alternative for applications in healthcare, workplace safety, and more.

# System Architecture

![Architecutrure_workflow_keynote 002](https://github.com/user-attachments/assets/e019cd8b-de24-4c1e-9a72-3cb1edbc2f86)

Our approach uses LSTM based architecute to predict the activity labels according to the input activity obtained from CSI data using two ESP32 microcontrollers one configured as reciever (rx) and other one configured as sender (tx). Collected raw CSI data is also available under this repository.

# Hardware Setup (configuring ESPs)


Two ESP32 micronctrollers - one for CSI sending (tx) and the other for receiving (rx) is to be flashed with the official ESP-CSI SDK.

# Data Collection Setup

![Data_collection_new (1)](https://github.com/user-attachments/assets/d9b95296-5ad2-4cdb-836a-57ddaf37b422)


We tested with two different envrironments with varyling light intensity considering volunteers of varying body shapes to bring in diversity for the data collected.

# Visualization of the data collected

![with_nofan_64](https://github.com/user-attachments/assets/36ceb653-f46d-4a6d-89c3-c6ca555504fd)


Here we plot the T-SNE for the obtained CSI data across three different activities.Optimizing systems for real-time data processing and activity recognition in dynamic environments.
By leveraging Wi-Fi CSI for HAR, systems can provide a cost-effective and privacy-conscious solution for monitoring human activities in various settings. 


