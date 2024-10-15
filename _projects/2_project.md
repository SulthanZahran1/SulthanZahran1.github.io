---
layout: page
title: GUI and Controller for 3D moving probe
description: Building a 2D Metal Surface Imaging Device
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

In the world of material science, understanding the intricate details of metal surfaces is crucial. Traditional methods like Scanning Capacitance Microscopy (SCM) offer detailed insights but often come with high costs and complexity. Enter my latest project: a cost-effective, 2D metal surface imaging device designed to generate detailed surface morphology maps without breaking the bank.

Project Overview
The goal was simple yet ambitious—to design and build a 2D metal surface imaging device that rivals traditional SCM in detail and accuracy but is more accessible for various applications. By leveraging affordable components and innovative design, this device opens up new possibilities for researchers and enthusiasts alike.

Key Features
1. High-Resolution Data Acquisition At the heart of the device is a 24-bit Analog-to-Digital Converter (ADC), ensuring precise and accurate data capture. This high-resolution data acquisition is essential for generating detailed surface morphology maps that can reveal even the slightest imperfections or features on a metal surface.

2. Automated Scanning Automation is key to efficiency and consistency. The device uses T8 and T3 stepper motors to move the probe and sample in two dimensions. This automated scanning capability allows for seamless data acquisition, reducing manual intervention and minimizing errors.

3. User-Friendly Interface Accessibility is a priority. I developed a graphical user interface (GUI) using Python and the Tkinter package, making it easy for users to control the device and visualize results. Whether you're a seasoned researcher or a hobbyist, the intuitive interface ensures a smooth user experience.

4. Simulation and Validation One of the challenges faced was the absence of a working capacitance sensor. To overcome this, I designed a simulation based on the DAC MCP4725. This simulated environment allowed for comprehensive testing and validation of the data acquisition system, ensuring the device's reliability even without the physical sensor.

Technical Details
The device employs stepper motors to control probe movement along the X, Y, and Z axes, enabling precise positioning for accurate data collection. An ADC ADS1232, paired with an Arduino Nano, measures voltage readings and transmits this data to a computer via serial communication. The Python-based GUI then processes the data and renders a 3D representation of the metal surface, with the Z-axis representing the measured ADC values. This real-time visualization provides immediate insights into the surface morphology, making analysis quicker and more efficient.

Overcoming Challenges
No project is without its hurdles. When the capacitance sensor couldn't be built due to unforeseen circumstances, I pivoted by designing a simulation using the DAC MCP4725. This workaround not only allowed the project to move forward but also provided valuable insights into the data acquisition process, ensuring the system's robustness and reliability.

Future Enhancements
While the current device is a significant achievement, there's always room for improvement. Future enhancements could include:

Integration of a Functional Capacitance Sensor: Bringing the physical sensor into the system will further enhance data accuracy and reliability.
Mechanical Design Refinement: Improving the mechanical components for greater stability and precision will lead to even more detailed surface maps.
Advanced Data Processing Techniques: Exploring alternative data processing methods could enhance image resolution and provide deeper insights into surface morphology.
Conclusion
This project is a testament to the power of innovative thinking and technical expertise. Designing, constructing, and validating a complex electro-mechanical system for 2D metal surface imaging showcased my ability to integrate various electronic components, microcontrollers, and programming languages to achieve a common goal. By providing a cost-effective alternative to traditional SCM, this device has the potential to make detailed metal surface analysis more accessible and widespread.

