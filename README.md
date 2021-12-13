# Deep-Fake-Image-Detection

## About
This project deals with the detection and classfication of an Image as either real or fake. A Common Fake Feature Network is trained over the dataset using the concept of Discriminative Learning to understand the fake features. A GUI of this model is built using Streamlit.

## Dataset Used
The [DeepFake Image Detection Dataset](https://www.kaggle.com/ciplab/real-and-fake-face-detection) from Kaggle, has been used for this project. This has 2041 images where 960 are fake and 1081 are real

## Technologies Used
1. **PyTorch** - Used to model the CFFN and the Classification Network
2. **Streamlit** - Used to build a Python GUI for the Classfication Network

## Steps to Run the GUI
1. Use the notebook _DeepFake_Image.ipynb_ on Colab (as this needs GPU runtime for execution)
2. Create a folder called saved_models on your Google Drive
3. Run the notebook (without the GUI cell) with any CFFN model of your choice, as many times as you'd like (NOTE:The different model names and syntax are in the Siamese Network Cell)
4. Ensure to save the models after training
5. Load any one of the trained models while training the GUI cell. 
6. Run the GUI using the _streamlit run_ command and wait for your URL to pop up. This will lead you to the GUI

**NOTE:** Steps 1 to 4 can be omitted if this notebook is being used for the second or subsequent time. You can simply load the models from the _saved_models_ folder on Google Drive
