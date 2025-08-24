# Driver Drowsiness Detection and Alert System

This project aims to design and implement a "Driver Drowsiness Detection and Alert System" using machine learning and embedded hardware such as the Raspberry Pi. The overall system will integrate multiple indicators of fatigue, such as blink rate, yawning, and head posture to detect signs of drowsiness in real time and trigger timely alerts, thereby improving road safety.

## Module 1: Blink Rate Detection

This modules forms one portion of the drowsiness criteria, focusing on blink rate analysis through Eye Aspect Ratio (EAR) calculations. EAR will also be applied in a separate module to detect prolonged eye closures.

The EAR is a scalar value that quantifies the state of the eye (whether it is opened/closed) by using specific eye landmarks to calculate the ratio between the eye’s height and width (Ahmad, Abdullah, & Nasrudin, 2019).

EAR adopts the following formula: 

$$
EAR = \frac{\lVert p_2 - p_6 \rVert + \lVert p_3 - p_5 \rVert}{2 \cdot \lVert p_1 - p_4 \rVert}
$$

## Citations

Citations are formatted in accordance with the APA 7th edition guidelines.

1. Ahmad, N. I., Abdullah, S. N. H. S., & Nasrudin, M. F. (2019). Real-time driver drowsiness detection system using eye aspect ratio. Jurnal Kejuruteraan, 31(2), 209–214. https://doi.org/10.17576/jkukm-2019-31(2)-04