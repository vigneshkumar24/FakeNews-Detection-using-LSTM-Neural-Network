# FakeNews-Detection-using-LSTM-Neural-Network
Technological advancements have drastically increased the amount of internet and social media users. An average user receives information from platforms like Facebook, Twitter, Reddit and Instagram. There is a high chance that the information is bogus and is specifically crafted to spread wrong information. Goal : To classify the Fake information using ML.


## **Steps to Run this Code**
---
1. The first step would be to clone this repo in a folder in your local machine. To do that you need to run following command in command prompt or in git bash
```Language
$ git clone  https://github.com/vigneshkumar24/FakeNews-Detection-using-LSTM-Neural-Network.git
```
2.This will copy all the data source file, program files and model into your machine.

3.Then Open the app.py which is insise the 'Model deployment using Flask' folder/directory
```python
model = joblib.load('C:\Users\Murugananthan\OneDrive\Studies\Lambton College\Second year\Term 3\AML 3104 Neural Networks and Deep Learning\Project\FakeNews-Detection-using-LSTM-Neural-Network\Model.pkl') #change the link according  to your folder/directory
```
4.After changing the folder/directory link run app.py by using IDLE(defult python Editer) or open the command prompt in the same directory and run the folloing code
```Language
$ python app.py
```
5.Then open this link http:localhost:5000/.

6.Then Enter the news in  Text box you want to check and click on submit.

7.Code will take user input text and will be used by model to classify in either of categories "True" and "False". 

8.Then the Flask server will return the result to your browser.
