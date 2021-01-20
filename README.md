# Pneumonia-Detection-web-app-using-Streamlit

## This project contains 4 main files each doing a different task. They are:
  * `Pneumonia Detection using CNN.ipynb`
    * Used to create train and evaluate a CNN model for detecting Pnuemonia. The dataset used to achieve this is 'Chest_Xray' dataset.
      The Model's performance and evaluation can be all figured from here
  * `Loading Pneum Det.ipynb`
    * Used to load the model which can be later verified and used separately, sparing us from the hectic training process of a model everytime it needs to be used
  * `my_model.h5`
    * Contains the saved CNN Model to be used
  * `main.py`
    * The streamlit web app coded which is used to take user X-Ray image input and predict the respective outcome.
    
## To run the project:
  * Pip install streamlit
  * use a python IDE of your choice (I used Spyder) and run main.py
  * from your terminal/command prompt, got to your directory containing *main.py* and type **streamlit run main.py** 
  * Localhost would be opened and use as per instructed on the webpage
  
 ## The dataset `chext_xray` used for training can be downloaded from [here](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
  

## Model Perforemance: 
  If you're interested in knowing what you are using, you can refer to the accuracy graphs below for the model I am using. 
  | col 1      | col 2      |
|------------|-------------|
| <img src=md images/ Capture.png width="250"> | <img src="https://mk0jobadderjftub56m0.kinstacdn.com/wp-content/uploads/stackoverflow.com-300.jpg" width="250"> |

Note:  `Pneumonia Detection using CNN.ipynb` & `Loading Pneum Det.ipynb` are just there for your own interest and are not required to run the project.
 
 
 
 Thanks & Enjoy!
