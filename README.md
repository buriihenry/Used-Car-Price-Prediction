## Deploying our Model using Flask
In this project I will show you how to deploy ML model using Flask 

### Requirements
You must have Scikit Learn, Pandas and Flask installed.

Flask version: 2.2.2
pip install Flask==2.2.2

### Running the project
1. Ensure that you are in the project home directory. Run the notebook "Used_Car_Price_Prediction" first

This would create a serialized version of our model into a file "model"

2. Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

3. Navigate to URL http://localhost:5000

You should be able to view the homepage.

Enter valid values in the form and hit Submit.

If everything goes well, you should  be able to see the predcited vaule on the HTML page!

$ add-stars -r

