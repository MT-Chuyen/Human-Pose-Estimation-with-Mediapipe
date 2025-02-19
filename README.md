# Human-Pose-Estimation-with-Mediapipe
Human Pose Estimation with Mediapipe

Authors: Assoc. Prof. Kien-Phan Nguyen, Chuyen-Tat Mai, Ly-Khanh Trinh, Trang-Huyen Thi Ong

Description: A research project to extract pose and measure angle in squat movement by phone based on 2D perspective, providing simple squat tracking solution for users

The paper is being submitted to conference ICISN 2025

## Individual role
_I served as the team leader. My key contributions included: pioneering the idea of using the thigh-vertical angle for squat assessment, collaborating on the design of the data acquisition system, leading the code development for pose extraction and angle calculation, and deriving the novel formula for calculating this angle from standard 2D video._

## Project Goals:

Problem Statement: Individuals new to fitness require precise training regimens to enhance techniques and reduce injury risk. Existing methods often involve costly coaching services.

Importance: Correct squat form is vital for athletic performance and injury prevention. Accessible and affordable solutions are needed.

Specific Objectives:

*   Develop a markerless approach to measuring the thigh-vertical angle during a squat.

*   Provide visual insight and assessment of squat form to the user.

*   Verify accuracy by comparing model estimations to actual data.

*   Provide practical methods to accurately measure squat depth, and evaluate the symmetry of squat motion.

Target Audience: Individuals new to fitness, biomechanics researchers, sports medicine, physical therapy.

## Methodology:

Overall Approach: Use computer vision and machine learning techniques to estimate squat form without markers.

Pose Estimation: Utilized the "MediaPipe Pose" machine learning pose estimation model to identify anatomical landmarks.

Angle Calculation: Calculated the angle between the thigh and the vertical axis using the coordinates of identified landmarks.

Camera setup: Set distance between the camera and users with an approximate relative height.

Verification/Evaluation:

*   Collected real data from 3 subjects (30 videos) with varying heights.

*   Compared estimated angles to angles measured manually with a protractor.

*   Calculated the Mean Absolute Error (MAE) to quantify accuracy.

*   Assessment for Motion Analysis Analyzed user movements on thigh symmetry and the angle between their thigh and the camera setup.

*   Open source and framework Model framework will be based on using OpenCV along with python.

## Results:

Performance: The average absolute error (MAE) was 4.3 degrees. This indicates that the thigh angle and vertical can be accurately measured using a machine learning solution to monitor body posture with high accuracy.

High Corelation: Corelation between the estimated and real values, and high reliability of the system. (P<0.001, and corelation >0.99)

Key Observation: The system can detect the deviation to ensure that the user is aware of the movement performance based on the camera setup.

Key Observation: The system can detect the deviation to ensure that the user is aware of the movement performance based on the camera setup.

 
