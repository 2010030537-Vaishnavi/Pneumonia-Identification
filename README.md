## Inspiration
Every year in India around 200-300 people die with pneumonia according to previous year statistics the major age group affected with pneumonia are above 70 and below 5 years old. Early detection of pneumonia is crucial for determining the appropriate treatment of the disease and preventing it from threatening the patient’s life. So we inspired to build a web app which detects pneumonia using lung X-ray images with greater accuracy.

## What it does
When the Person drops lung X-ray our deep learning model which will tell us whether the person is having pneumonia disease or not having pneumonia.

## How we built it
We used deep learning models VGG16 and Transfer learning to train and test the dataset each with two hidden layers. Chest X-rays dataset is taken from Kaggle which contain various x-rays images differentiated by two categories “Pneumonia” and “Normal”. Html ,CSS ,JS and python framework flask are use for frontend.

## Challenges we ran into
While working with this project we came across many models. Incorporating models correctly in our project is quite challenging in a short period of time. At the same time we also faced hardship while deploying using flask and gunicorn.

## Accomplishments that we're proud of
We're really proud after completing this project with 96% accuracy

## What we learned
We learnt models like VGG16 and TL which are complete new to us. Even though we are little familiar with flask deploying as web-app is challenging which we accomplished.

## What's next for Pneumonia Identification
Further we can create a single web app for various lung diseases such that when the person drops his/her lung X-ray our web-app detects if he is having any lung disease such as Covid-19 - Asthma-Pneumonia or normal.
