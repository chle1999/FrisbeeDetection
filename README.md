# Frisbee Detection

## Introduction

Frisbee Detection is an open-source project designed to assist ultimate frisbee teams and disc enthusiasts in capturing their playing moments effortlessly. Due to the size of the field and limited camera viewing angles, current recording methods often require a person on the sideline to hold a phone or camera, resulting in unstable and blurred videos. Our goal is to leverage computer vision techniques and gimbal technology to automatically detect, track, and record the disc and players, ensuring that no important moments are missed.

## Our Goal

With one phone installed with our app and one gimbal, you can easily set up your recording system.

## Getting Involved

As an individual developer, my knowledge and capabilities are limited. Therefore, if you are interested in this project and have experience in Object Tracking, UI Development, or Gimbal Control, I invite you to collaborate with me. Please reach out at yangchle1999@gmail.com. Additionally, if you have any creative ideas or suggestions, feel free to send me an email.

## Setup

To avoid additional costs, we would like to use DJI OSMO Mobile 6 as our default platform. We may support more gimbal models or brands in the future if everything goes well.

## Future Plans

Here is the roadmap for the development of this project:

1. **Disc and Player Detection and Tracking on PC**: Utilize YOLOv8 Nano and TensorFlow to detect and track the disc and players on a personal computer.<br>
   * Develop and Train YOLOv8 Nano Model including image extraction, labeling and training.<br>
   * Develop and Test Real-Time Tracking by converting the trained YOLO model to TensorFlow Lite format.<br>
   
2. **Mobile App Development**: Create a mobile application incorporating the functionality developed in phase 1.<br>
   * Set Up Mobile Development Environment.<br>
   * Integrate TensorFlow Lite with Android App.<br>

3. **Gimbal Control Integration**: Implement gimbal control to synchronize with the object tracking system.<br>
4. **Mobile App Gimbal Control**: Integrate gimbal control features into the mobile application.<br>
5. **Additional Features**: Enhance the application with features such as game data analysis, specific player detection, and live streaming capabilities.<br>

## Collaborators

(Alphabetically by surname)
- Liu Yihan
- Yang Chengle
- Yang Yuxin

## Specific Thanks

Our training and testing dataset providers.

## Contact

If you're interested in contributing to this project, or if you have any questions or suggestions, please contact me at yangchle1999@gmail.com.
