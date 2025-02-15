# Prosthetic-Finger-Control-using-EMG-Signals

📌 Overview
This project focuses on controlling a prosthetic finger through electromyography (EMG) signals, captured from the brachioradialis muscle in the forearm. The project utilizes EMG signal processing, including measurement, rectification, smoothing, and gain adjustment, to refine raw muscle signals. The processed signals are then fed into a microcontroller to control a servo motor that actuates the prosthetic finger.

The system features two key control modes:

Proportional Control: Adjusts the prosthetic finger's movement based on the intensity of the muscle contraction.

Sequential Control: Detects specific patterns of muscle activity and triggers predefined movements or gestures of the prosthetic finger.

⚙️ Key Features

EMG-Based Control: The prosthetic finger is controlled using signals from the brachioradialis muscle, allowing for intuitive and natural movements.

Proportional Control: The finger's movement is directly proportional to the intensity of muscle contractions.

Sequential Control: The system can interpret muscle activity sequences and trigger specific finger movements or gestures.

Signal Processing: Includes stages of rectification, smoothing (filtering), and gain adjustment for effective signal interpretation.

Real-Time Control: The system works in real-time with minimal delay for accurate and responsive control.

Embedded System: The prosthetic finger prototype runs on an embedded development board, eliminating the need for laptops or PCs.

🔧 Components Used

Electrical Components & Actuators:

SG90 Servo Motor

Arduino Microcontroller

EMG Sensor

Sensing Electrodes

9V Battery

Jumpers

Mechanical Parts:

3D Printed Finger Components

M3 Bolts for assembly

⚠️ Design Challenges

Range of Motion: Achieving natural movement of the prosthetic finger, similar to a human hand, requires precise engineering and overcoming mechanical challenges like backlash and friction.

Sensory Feedback: Providing realistic sensory feedback for user interaction with the environment.

Weight and Size: Balancing weight and size for comfort and practicality in prolonged use.

Adaptability: Ensuring the prosthetic can perform different grips and tasks effectively.

🛠️ Project Phases

Proportional Control: Focuses on establishing a direct relationship between muscle contraction intensity and prosthetic finger movement.

Sequential Control: Detects muscle activity patterns to trigger specific gestures or actions, providing more complex functionality.

🔄 Control System

The EMG sensor captures muscle signals, which are processed and interpreted by the microcontroller to control the movement of the prosthetic finger. The software includes several filters (second-order, RMS, EMA) to reduce noise in the EMG signals and enhance control responsiveness.
