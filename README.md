# Brain Computer Interface Project

The project has been realized in my final year at engineering school in the Man and Machine module.

This project aims to develop a system for classifying electroencephalographic (EEG) events using machine learning models. The study uses EEG recordings from two subjects (Subject 10 and Subject 11) to train and evaluate the models.

The process includes several steps, such as reading the EEG data, preparing the data with techniques such as mean spectral power (MSP) transformation, normalising the data, and using different algorithms such as Random Forest, XGBoost, AdaBoost.

The "Leave One Out" approach is used to evaluate the performance of the models on the training dataset, and the results are presented in the form of confusion and accuracy matrices.

The final model is a combination of soft vote classifiers, including AdaBoost, Random Forest, and XGBoost. The final model is saved for future use.

The overall aim of the project is to explore and develop classification methods for EEG signals, with a particular focus on generalising models from training data to unknown data. Results and critical analyses are presented for a thorough performance evaluation of the proposed system.

# Run the project

To run the project, installations are needed :

```
conda install -c conda-forge mne

conda install -c conda-forge pyvistaqt

conda install -c conda-forge ipywidgets

conda install -c conda-forge darkdetect
```

Then, the notebook called "Brain_Computer_Interface.ipynb" can be executed.
The final model can be load via Joblib, the name is "EGG_Classifier.joblib"
