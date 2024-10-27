This is the final year project of Sia Ping Hui.

The objective of this project is to design a vehicle license plate recognition model using YOLO-NAS object detection and EasyOCR as optical character recognition, and to recognize and identify the vehicle license plate number under challenging conditions using the model. The model was trained and tested on different experiments to identify the performance of the model. 

The proposed model is to use YOLO-NAS as an object detection model and optical character recognition model. The proposed model was tested on recognizing vehicle license plate under four different condition: (1) Visible license plate under normal condition; (2) Vehicle license plate under occluded/obscured condition; (3) vehicle license plate under foggy/hazy weather condition, (4) vehicle license plate under raining conditions. 

The test done on the model was to test the performance when running the model, the rate of success detection of vehicle license plate of the model, and the accuracy of the model in recognizing the license plate number. The model was trained using 1013+ images dataset from roboflow and was tested with valid dataset of 50 normal condition, 10 obscured condition, 10 hazy condition, and 10 raining condition. All the tests done on the model were in 3 iterations, and the results were taken and analyzed. 

Overall, the proposed model yields a result of 93.22% when recognizing license plate under normal conditions, 93.0% when recognizing under obscured condition, 93.21% under hazy condition, and 85.9% under raining condition. The result had shown that the proposed method is valid and able to perform on-par with existing method for recognition under challenging conditions.

https://github.com/Icesuu/FYP/blob/main/Image.PNG
