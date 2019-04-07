# Lane_Detection
Lane detection using deep learning (Fully Connected CNN) and OpenCV

In this project we will detect lane lines in images using two approaches. First approach using opencv, canny edge detector and hough transform algorithms. In the second approach we build a deep learning model using fully connected CNN pretrained model to detect lane in a image.

**Approach 1 :**

Running the model :
```
cd Approach-1

jupyter nbconvert --execute run.ipynb
```

**Approach 2 :**

Training the model :
```
cd Approach-2

python model.py
```

Testing the model:
```
jupyter nbconvert --execute run.ipynb
```

**References :**\
[1] Chuan-en Lin (2018 , Dec. 17). “Tutorial: Build a lane detector”, Available: https://towardsdatascience.com/tutorial-build-a-lane-detector-679fd8953132.[Apr 06, 2019]\
[2] Aydin Ayanzadeh (2018 , Mar. 19). “Udacity Advance Lane-Detection of the Road in Autonomous Driving”, Available:https://medium.com/deepvision/udacity-advance-lane-detection-of-the-road-in-autonomous-driving-5faa44ded487.[Apr 06, 2019]\
[3]Udacity, self-driving-car, (2017), GitHub repository, https://github.com/udacity/self-driving-car.[Apr 06, 2019]
