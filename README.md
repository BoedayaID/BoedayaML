# BoedayaML
## How to use this ML model:
### 1. First, place your dataset in 'Dataset Preparation/Dataset/' directory.
### 2. Run 'audio_length_adjustment.ipynb' inside Dataset Preparation folder and wait for it to finish.
### 3. Run 'audio_data_augmentation.ipynb' inside Dataset Preparation folder and also wait for it to finish.
### 4. Run 'dataset-labelling.ipynb' inside Dataset Preparation folder and once again, wait for it to finish.
### 5. Locate 'dataset.json', it should be located inside the same folder as 'dataset-labelling.ipynb' file, then copy it to 'Model' directory.
### 6. Run 'model.ipynb' inside Model folder and wait for the training to be finished, an h5 file should be created automatically.
### 7. Your own ML model is done and saved in h5 format. If you want to run prediction on the model, run 'prediction.ipynb' and pick the audio file to predict.
