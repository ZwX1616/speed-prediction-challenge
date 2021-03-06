# Predict speed of car from dashcam video
Comma.ai challenge to predict speed from a dashcam video

Split up the data into train(90%) and validation(10%). 
<br>
MSE -
 - Train - 4.4575
 - Validation - 1.089

Train_graph | Validation Graph
 --- | --- 
![Train Graph](/train_graph.png) | ![Validation Graph](/validation_graph.png)

Key points are tracked using a mask as shown in the sample gif. Rotation of camera is not considered.
![Car View](/car_view.gif)

Referred to this [blog post](https://nicolovaligi.com/car-speed-estimation-windshield-camera.html) for some guidance and [this implementation](https://github.com/quillford/speedchallenge) for hyperparameters. You can also refer to these [slides](http://www.cse.psu.edu/~rtc12/CSE486/lecture22.pdf) for the math behind deriving the optical flow parameters.

## TODO:
 - [x] - Compute MSE for both train and val
 - [x] - Graph for both train and validation
 - [x] - Video showing key points