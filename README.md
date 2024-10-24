# multi-resolution_fusion_sleep-apnea
Code for the paper ``Multimodal Multiresolution Data Fusion Using Convolutional Neural Networks for Wearable Sensing."

Please cite the article if using this resource: A. John, K. K. Nundy, B. Cardiff and D. John, "Multimodal Multiresolution Data Fusion Using Convolutional Neural Networks for IoT Wearable Sensing," in IEEE Transactions on Biomedical Circuits and Systems, vol. 15, no. 6, pp. 1161-1173, Dec. 2021, doi: 10.1109/TBCAS.2021.3134043.

1. sleep_apnea_ecg.ipynb shows the ECG model development. Model parameters stored in best_weights_ecg_32layer.hdf5.

2. sleep_apnea_spo2.ipynb shows the SpO2 model development. Model parameters stored in best_weights_spo2_3_312layer.hdf5.

3. sleep_apnea_only_abdo_GPU.ipynb shows the abdomial model development. Model parameters stored in best_weights_abdo_32layer.hdf5.

4. sleep_apnea_ecg_spo2_fusion.ipynb shows the ECG+SpO2 model development. Model parameters stored in best_weights_fusion_10_12.hdf5.

5. fusion_abdo_spo2.ipynb shows the SpO2+Abdo model developmet. Model parameters stored in best_weights_fusion_spo_abdo_9_2.hdf5. An example of fusion without selective dropout is provided for this model in fusion_abdo_spo2_wo_dropout.ipynb with model parameters stored in best_weights_fusion_spo_abdo_18_8_wo_drop.hdf5.

6. sleep_apnea_fusion_files_ecg_abdo.ipynb shows the ECG+Abdo model development. Model parameters stored in best_weights_fusion_abdo_ecg_14_2.hdf5.

7. sleep_apnea_fusion_files_all3.ipynb shows the ECG+SpO2+Abdo model development. Model parameters stored in best_weights_fusion_abdo_17_8.hdf5.

The google drive at which the raw and processed data was hosted has expired. New location will be updated here soon.
