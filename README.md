# Customer Counter (Final TSA Project)
The CustomerCounter project aims to address the need for an efficient and automated system to calculate the number of customers for business owners. Traditionally, this task has been carried out manually by hiring security guards to count incoming customers. However, this approach is considered outdated and inefficient.

In this project, the team aims to develop a system that automates the process of customer counting. The system utilizes object detection technology to identify humans entering the premises. By using a camera, the system detects the presence of an object and verifies if it is a human. The detected object's count is then transmitted to the MQTT dashboard platform, allowing users to easily monitor and track customer numbers.

To implement the system, an HC-SR04 sensor is employed to detect incoming objects, such as humans. Additionally, a buzzer is incorporated to provide auditory notifications when someone enters or leaves the room. An LCD display, specifically a Running Text display, is utilized to present the real-time count of customers inside the room.

By automating the customer counting process, the CustomerCounter project offers businesses an efficient and accurate method to track and manage customer flow. The system eliminates the need for manual counting, reducing human error and saving resources. With real-time data available on the MQTT dashboard, businesses can make informed decisions and optimize their operations based on customer traffic patterns.
## Team Members
A list of peoples who participated in this project:
* Andriy Athalla Alrasheed (Machine Learning Programmer)
* Eka Mahendra Bagaskara (Hardware Engineer)
* Firman Rachmad Caesar (Microcontroller Programmer)
* M. Alif Ali Al-Barsyah (Hardware Engineer)
## Project Testing
![Screenshot_3](https://user-images.githubusercontent.com/72642653/236965641-ec4e89d1-2e4b-4d6f-a150-8024ede27b37.png)

1. The testing circuit of our project. The purpose is to test that every sensor and actuator are working properly before we make the system's prototype.

![Screenshot_7](https://user-images.githubusercontent.com/72642653/236966209-73589248-e7b1-466a-b786-4414aca1c401.png)

2. Testing the HC-SR04 sensor.

![Screenshot_2](https://user-images.githubusercontent.com/72642653/236966793-24f7d135-2834-4709-ab27-6634037d84ab.png)

3. The testing of the LDR module sensor and our project's rule. The condition is that there are more than 3 people captured by HC-SR04 and verified by the camera in the room, and there is a lack of lighting. And the result is that two lamps are turned on by the relay.
## Prototype Results
_NOTE : We also add the LCD Module in this prototype to preview the current total number of the customers that are detected by our system._

![Screenshot_1](https://user-images.githubusercontent.com/72642653/236968250-dbf740cf-0018-4260-82ef-e55c8811fd73.png)

![Screenshot_5](https://user-images.githubusercontent.com/72642653/236968721-950ba61e-f17d-4030-b591-e181071def2a.png)

![Screenshot_4](https://user-images.githubusercontent.com/72642653/236968795-4a7dad23-809b-480b-b9e1-ad417a44384a.png)

![Screenshot_6](https://user-images.githubusercontent.com/72642653/236968934-2236d2af-2365-4915-bb4d-ed648a171ed9.png)
## Projects Demo Video

* https://drive.google.com/file/d/1PG5IzxoYHWILlEf43pq881OQ8VnQxglM/view?usp=sharing
* https://drive.google.com/file/d/1dqmEi3BDaft5ZIc7BGejV1-BXR-USxlP/view?usp=sharing
