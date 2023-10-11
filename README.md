Lack of surveillance and untimely arrival of firefighters can cause even a small fire to cause huge devastation in our daily lives. So, detecting the fire and alerting the officials as early as possible becomes a crucial task in controlling this issue. Thus, we have created an architecture using Raspberry Pi and a camera to detect fire and people trapped. The system consists of two modules: fire detection and people detection.

In order to provide an accurate number of people trapped in the building find the location of trapped people and detect the fire using the Inception V3 algorithm which is embedded in the vision node, i.e., camera and Raspberry Pi. 

We use Convolution Neural Networks (CNN) with Mobile Net SSD for detecting people stuck in the area of fire accidents obtained from a pre-trained model. TensorFlow package is also integrated into the system for detecting people and fire. A user interface is developed and integrated with the vision node through a local server for visualizing the real-time events in the building related to the fire and getting the count of people. 

In the proposed system, live surveillance will be provided through the user interface and a people detection report will be generated depicting the headcount of people, average accuracy of the result, an enumeration plot, and an accuracy plot.

