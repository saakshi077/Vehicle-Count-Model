# Aim : Vehicle Count Model

My approach to the model.
My approach uses unsupervised object detection as no labeled data was given by default.For this I  used frame differencing technique using Python and OpenCV.
I extracted Foreground Mask by Background Subtraction .Then after applying Image Dilation and Image Thresholding,  Contours are identified 
And finally the frames near the detection Reference line are counted by the Vehicle Counter as the vehicle approaches the Reference line (in red).

## What other model could you have used for the same?
There are various techniques and approaches to solve this problem.  To name a few,
 R-CNN, Fast R-CNN, Faster R-CNN, YOLO
TheseDeep Learning Models  are Pre- Trained Models and then we fine tune the model according to our data. For this kind of approach we require labeled data to train the object detection model (which in our Assignment was not given).
Why did you choose that model?
I chose this model as I was given only 3 videos + no additional data. Its is already a very complex task to deal with videos and I wanted to make it as simple as possible and less time consuming. I realised there was no need to train this on complex and large Pre Trained Models. I made my own model customized as per the data given to me.

 Why is your current model better than other models?
 
* No data required for labeling 
* Fast & Adjustable 
* No huge time Required for training models

![Screenshot 1](https://i.imgur.com/Zyg6OAU.png)
![Screenshot 2](https://i.imgur.com/szCRkf5.png)
![Screenshot 3](https://i.imgur.com/lQeRQeN.png)
