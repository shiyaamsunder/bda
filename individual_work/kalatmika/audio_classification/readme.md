# UrbanSound8K Audio Classification

## Development

### Setup
- Install dependencies
    ```sh
    pip install -r requirements.txt
    ```
- Move the dataset to the `dataset` folder. The dataset folder should be like this:
    ```
    dataset
    ├── fold1
    ├── fold2
    ├── fold3
    ├── fold4
    ├── fold5
    ├── fold6
    ├── fold7
    ├── fold8
    ├── fold9
    ├── fold10
    └── UrbanSound8K.csv
    ```
- Run the notebook as you like (VSCode, Jupyter Notebook, etc.)

### Outputs

- The trained model is saved as `audio-classification.keras` in the `results` folder. You can load the model and predict the audio class from a new audio file (after extracting features from it using `librosa`).