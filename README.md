# Device Free Human Activity Recognition Using Wi-Fi CSI

We use the Channel State Information (CSI), containing the amplitude & phase of subcarriers, of a Wi-Fi signal obtained using two ESP32 devices configured as transmitter & receiver to correctly predict & classify the presence of a human being & the physical activity they are performing. This is done by training recurrent neural networks on the recorded CSI data.
We have explored several model architectures & hyper parameters to improve the robustness of the model on unseen data & varying environments.