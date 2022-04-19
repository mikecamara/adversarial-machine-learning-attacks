# Using Adversarial Defense Methods to Improve the Performance of Deep-Neural-Network-Controlled Automatic Driving Systems

Master’s Thesis (30 ECTS) - University of Tartu and TalTech - Software Engineering Curriculum

![Eperiment Video Demo](https://user-images.githubusercontent.com/8085864/163942155-b5d5670f-08c3-4303-a227-5c4a658a8024.png)

## Useful links

* [Experiment Video Demo](https://youtu.be/A_dHfvMgd-w)
* [Thesis PDF Document](PDF/Camara_Software_Engineering_2022.pdf)
* [Supervisor Meeting Logs](supervisor-meetings-logs/README.md)
* [Data Extraction Table](https://docs.google.com/spreadsheets/d/1hK-wXvBYuIYqfd0BKTh8oYs5C-CKyelPAqyBtdPVJfQ/edit?usp=sharing)
* [Thesis LaTeX Document](https://www.overleaf.com/read/fczpcqqmknvp)
* [Code](code/README.md)


## Topic - ADS
To create Automatic Driving Systems (ADS), engineers rely on a range of sensors attached to a vehicle or a robot, including radar, lidar, high definition cameras, and GPS. However, creating an automatic driving system entirely controlled by a Neural Neural network using a single RGB camera is also possible.

The process is called behavioral cloning and involves training a convolutional neural network (CNN) with many good driving examples. In other words, an expert operates the vehicle, collecting images that are labeled with throttle and steering values. This data is then used to train a CNN model capable of automatically driving in the route it has been trained. 

## The problem

The problem with this approach is that the neural networks tend to overfit the training data. It performs well in the conditions exposed during training, including the lighting conditions, and performs poorly in never-seen-before lighting conditions. So, a CNN trained with images captured in the daytime is unlikely to perform well at night. To solve this issue, engineers have to spend a lot of time collecting data in different lighting conditions, but this is not always possible because of time constraints or weather conditions. Thus, new training methods must be investigated.

## Reseach question

**Can adversarial defense training methods improve the neural network’s generalization skills to unseen lighting conditions?**

## Hypothesis

The hypothesis is that the CNN models trained with adversarial machine learning defense methods will perform better in unseen lighting conditions than CNN models trained with standard procedures. 

## Results

The CNN models trained with adversarial machine learning defense methods did perform better in never-seen-before lighting conditions than CNN models trained with standard procedures. 

The models M-TS and M-TL, trained with standard methods, failed to generalize to the unseen higher lighting (H), having several collisions against the wall. On the other hand, the models trained with adversarial methods performed well in the unseen higher lighting (H), completing two laps without collisions. 

![results](https://user-images.githubusercontent.com/8085864/163939722-257b463f-7ff8-467e-8aad-af7eb5cb658c.png)

<hr>


## License

The content of this project itself is licensed under the [Creative Commons Attribution 3.0 Unported license](https://creativecommons.org/licenses/by/3.0/), and the underlying source code used to format and display that content is licensed under the [MIT license](LICENSE.md).