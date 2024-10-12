# Fork Information
This repository is a fork of the `MIC-DKFZ/nnUNet project`. For detailed usage instructions specific to nnUNet, please visit the original repository.

# Training Weights for the SCOUT Study
The trained weights for the SCOUT study can be downloaded from [this Google Drive link](https://drive.google.com/drive/folders/1gajvavkI6iJogJK_OcV7ZntBJ-1OQa3_?usp=drive_link). The folder contains the complete training results.

# Using the Trained Weights on Your Data
To use the trained weights for inference on your own data, refer to the `nnUNet/nnunetv2/inference/predict_from_raw_data.py` script for guidance on applying the model. You will need to modify the predictor object and adjust the file paths to match your data locations.
Please note, the model was trained on 256x256 grayscale NiFti slices, so ensure your data is preprocessed accordingly for optimal performance.
