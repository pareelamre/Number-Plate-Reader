# Number-Plate-Reader
Developed a number plate reader using Object Detection and OCR filtering

As part of this assignment, I learned how to build a number plate reader that identifies a number plate from a given image and reads out the characters of the number plate. 
Dataset
I used a pre-annotated dataset to train the Object detection model. The dataset can be found at this link: https://www.kaggle.com/datasets/andrewmvd/car-plate-detection

Method
The following processes were followed to achieve the desired result:
1.	Installing and setting up modules
2.	Getting License plate data
3.	Training an object detector model
4.	Detecting license plates
5.	Applying Optical Character Reader(OCR) to text
6.	Output Region of Interest(ROI) and results

Result
![image](https://user-images.githubusercontent.com/35176680/210173581-0bf036ac-959f-4c32-a7d9-47a357dca881.png)

 
Inference
This project was made with the objective of reading the Number plates of cars. I have noticed in many places around me that cameras are installed everywhere to check what goes on around the city. However, there is still a need for policemen to stand on the roads and comb through the busy traffic to check for people not following traffic rules. In a densely populated country like India, traffic cameras with the ability to read the number plates of vehicles will go a long way in helping the traffic police to look out for anomalies.
The number plate can act as a primary key for every individual vehicle. The number plate will list down the owner’s name and other details related to them, and fines can accordingly be cut without any physical interference between the authority and the driver of the vehicle.
