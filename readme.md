# Fork Information
This repository is a fork of the `MIC-DKFZ/nnUNet project`. For usage instructions, please visit the original repository: https://github.com/MIC-DKFZ/nnUNet

# Training Weights for the SCOUT Study
The trained weights for the SCOUT study can be downloaded from this Google Drive link: https://drive.google.com/drive/folders/1hiY6V6Uox4MQkXs1u5yaCL1IBu_hCv3X?usp=sharing. The folder contains the complete training results.

# Using the Trained Weights on Your Data
To use the trained weights with your own data, refer to `the nnUNet/nnunetv2/inference/predict_from_raw_data.py` script for instructions on applying the model. Please note, the model was trained on 256x256 grayscale NiFti slices, so ensure your data is preprocessed to match these dimensions for optimal performance.
