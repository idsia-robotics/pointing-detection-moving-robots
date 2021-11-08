# Pointing  at  Moving  Robots:  Detecting  Events  from  Wrist  IMU  Data

*Gabriele Abbate, Boris Gromov, Luca M. Gambardella, and Alessandro Giusti*

Dalle Molle Institute for Artificial Intelligence, USI-SUPSI, Lugano (Switzerland)

### Abstract

We propose a practical approach for detecting the event that a human wearing an IMU-equipped bracelet points at a moving robot; the approach uses a learned classifier to verify if the robot motion (as measured by its odometry) matches the wrist motion, and does not require that the relative pose of the operator and robot is known in advance.  To train the model and validate the system, we collect datasets containing hundreds of real-world pointing events.  Extensive experiments quantify the performance of the classifiers and relevant metrics of the resulting detectors; the approach is implemented in a real-world demonstrator that allows users to land quadrotors by pointing at them.

The paper has been accepted at ICRA 2021. The submitted pdf is available [here](https://ieeexplore.ieee.org/document/9561387)

### ICRA Video Submission (click to open on youtube)

[![Pointing  at  Moving  Robots:  Detecting  Events  from  Wrist  IMU  Data](https://github.com/idsia-robotics/pointing-detection-moving-robots/blob/main/videos/Pointing_at_Moving_Robots_Detecting_Pointing_Events_from_Wri.gif)](https://www.youtube.com/watch?v=x7Xt7Xr7pWk&ab_channel=BorisGromov)

Cite this work:
```
  @INPROCEEDINGS{9561387,
    author={Abbate, Gabriele and Gromov, Boris and Gambardella, Luca M. and Giusti, Alessandro},
    booktitle={2021 IEEE International Conference on Robotics and Automation (ICRA)}, 
    title={Pointing at Moving Robots: Detecting Events from Wrist IMU Data}, 
    year={2021},
    volume={},
    number={},
    pages={3604-3611},
    doi={10.1109/ICRA48506.2021.9561387}
  }
```
