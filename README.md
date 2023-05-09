# Customer Counter (Final TSA Project)
Calculation of the number of customers is necessary for business owners, this is because with information about the number of customers, businesses can grow. But with the system used so far, the calculation of customers is done manually by hiring a security guard to help count incoming customers. This system is considered less efficient and outdated, therefore in this project the team wants to create a system to help count customers automatically. The object to be detected is a human, where the system will detect if an object enters and check whether the object is detected as a human by the system from the camera, then the system will send the results of the object calculation to the mqtt dashboard platform so that it can be seen by the user. This project requires an HC-SR04 sensor to detect incoming objects, as well as a buzzer to notify that someone is entering or leaving the room, and an LCD (Running Text) to display the number of customers in the room.
## Team Members
A list of peoples participate in this project:
* Andriy Athalla Alrasheed (Machine Learning Computer Vision Camera Programmer)
* Eka Mahendra Bagaskara (Hardware Engineer)
* Firman Rachmad Caesar (Microcontroller Programmer)
* M. Alif Ali Al-Barsyah (Hardware Engineer)
## Project Testing
![Screenshot_3](https://user-images.githubusercontent.com/72642653/236965641-ec4e89d1-2e4b-4d6f-a150-8024ede27b37.png)

1. The testing circuit of our project. The purpose is to test that every sensors and actuator working properly before we make the system's prototype.

![Screenshot_7](https://user-images.githubusercontent.com/72642653/236966209-73589248-e7b1-466a-b786-4414aca1c401.png)

2. Testing the HC-SR04 sensor.

![Screenshot_2](https://user-images.githubusercontent.com/72642653/236966793-24f7d135-2834-4709-ab27-6634037d84ab.png)

3. The testing of LDR module sensor and our project's rule. The condition is there are more than 3 peoples captured by HC-SR04 and verified by the camera in the room that is lack of lighting. And the result is 2 lamps is turned on by the relay.
## Prototype Results
_NOTE : We also add the LCD Module in this prototype to preview the current total number of the customers that are detected by our system._

![Screenshot_1](https://user-images.githubusercontent.com/72642653/236968250-dbf740cf-0018-4260-82ef-e55c8811fd73.png)

![Screenshot_5](https://user-images.githubusercontent.com/72642653/236968721-950ba61e-f17d-4030-b591-e181071def2a.png)

![Screenshot_4](https://user-images.githubusercontent.com/72642653/236968795-4a7dad23-809b-480b-b9e1-ad417a44384a.png)

![Screenshot_6](https://user-images.githubusercontent.com/72642653/236968934-2236d2af-2365-4915-bb4d-ed648a171ed9.png)
## Projects Demo Video

* https://drive.google.com/file/d/1PG5IzxoYHWILlEf43pq881OQ8VnQxglM/view?usp=sharing
* https://drive.google.com/file/d/1dqmEi3BDaft5ZIc7BGejV1-BXR-USxlP/view?usp=sharing
