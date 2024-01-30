
## Acknowledgments
* [Yolov3 TensorFlow 2 Amazing Implementation](https://github.com/zzh8829/yolov3-tf2)
* [Another Yolov3 TensorFlow 2](https://github.com/heartkilla/yolo-v3)
* [Yolo v3 official paper](https://arxiv.org/abs/1804.02767)
* [A Tensorflow Slim implementation](https://github.com/mystic123/tensorflow-yolo-v3)


# NextGenShifters - The New Way of Moving

# Problem Statement: # 
The traditional packers and movers industry lacks transparency in its pricing model, leaving clients unaware of the basis for charges. The current practice of determining truck size solely based on the house size is flawed, as it doesn't consider the actual number of items. Additionally, clients are in the dark about the pricing breakdown, leading to a lack of cost transparency.

# Objectives:
•	Create a transparent pricing model.
•	Improve accuracy in truck size determination.
•	Simplify user experience by requiring only essential information.

# Approach:
To address these issues, we have developed "Next Gen Shifters," a web-based business prototype for the packers and movers industry. Our goal is to revolutionize the pricing model by leveraging object detection, machine learning, and distance matrix API.

# 1.	Object Detection and Truck Size Determination:
•	Users upload images of their residence on our website.
•	Object detection algorithms (such as YOLO) identify major objects, helping determine the truck size needed.
•	Truck size is determined not solely based on house size but on the actual count of major objects, ensuring a more accurate match.
# 2.	Distance Calculation:
•	Users provide origin and destination addresses.
•	Distance matrix API calculates the shortest distance between the two locations.
# 3.	Pricing Model:
•	A fair and transparent pricing model is created based on:
•	Truck cost determined by the size identified through object detection.
•	Fragile item cost calculated by counting fragile items.
•	Labor cost set at a fixed rate.
•	The entire process is automated for efficiency.
# 4.	Backend Processing:
•	User inputs are processed in the backend through the following steps:
1.	Input collection (images, origin, and destination addresses).
2.	Object detection identifies fragile and major items.
3.	ML model predicts the count of major items.
4.	Truck size is determined based on the ML model output.
5.	Distance matrix API calculates the shortest distance.
6.	Total cost is calculated, considering truck cost, distance, fragile item cost, and labor charge.
7.	The final cost is displayed to the user.



# Conclusion: 

Next Gen Shifters aims to redefine the online packers and movers industry by introducing a transparent, efficient, and fair pricing model. Our approach, integrating object detection, machine learning, and distance calculation, ensures accuracy in truck sizing and cost determination. The user-friendly interface makes the shifting process seamless for our clients.
