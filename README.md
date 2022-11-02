# [Multiple Disease Detector](https://pneumoniadetector.azurewebsites.net)

## About

This webapp was developed using Flask Web Framework and is deployed on Microsoft Azure. The model used to predict the disease was trained on a large Dataset. All the links for datasets and the model used for model creation are mentioned below in this readme. The webapp can predict following Diseases:

- Diabetes
- Pneumonia

## Model with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Diabetes       | Machine Learning Model   | 98.25%   |
| Pneumonia      | Deep Learning Model(CNN) | 95%      |


## Microsoft azure service used :

- Azure web apps service


## Group Members
- Group Rep : 
  [Kuber Anand](https://github.com/KuberAnand)
  [Ishaan Taneja]


## Deployment Screnshots :

1. Home page
![Capture](https://user-images.githubusercontent.com/80303856/155894623-24371b54-0a62-452f-8867-8efa11732394.PNG)

2. Uploading the x-ray for prediction
![Capture2](https://user-images.githubusercontent.com/80303856/155896486-427de6fa-755a-45e3-a58d-481e8ab6b996.PNG)

3. Prediction of our model on x-ray
![Capture3](https://user-images.githubusercontent.com/80303856/155896511-2ce59279-9694-472e-9e2e-91b1a9fc25ba.PNG)

## NOTE

==> You can access the website live at: https://pneumoniadetector.azurewebsites.net/ <br>
==> Python version 3.7 was used for the whole project.<br>

## Demo Video


https://user-images.githubusercontent.com/80303856/156380630-f3eeb375-e535-43e1-b5b2-b02de86313e3.mp4



## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle.

- [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
