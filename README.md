# Device Free Human Activity Recognition Using Wi-Fi CSI

---

## Project Overview

This project leverages Channel State Information (CSI), which includes both the amplitude and phase information of multiple subcarriers of a Wi-Fi signal, reflecting the channel's response between the transmitter and receiver, to detect human presence and classify physical activities. The CSI data is collected using two ESP32 devices configured as a transmitter and a receiver. Our approach involves training recurrent neural networks (RNNs) on the recorded CSI data to accurately predict human presence and the activity being performed. We have experimented with various model architectures and hyperparameters to enhance the model's robustness on unseen data and in diverse environments.