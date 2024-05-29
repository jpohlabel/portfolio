# Health Hub
2024

## Background
This was my senior capstone project. I worked on this with 3 other computer science students and 5 biomedical engineering students. Our sponsor was a biomedical engineering professor at Ohio State.

## Description
We were tasked with creating a health UI dashboard to read in data from several different Arduino sensors, such as a blood pressure, heart rate, EKG, and oxygen sensor. These sensors plugged into Arduino microcontrollers,
which then transmitted data to a Raspberry Pi that was running the web app to display the data. There was also a digital dial that could be used to control the flow of anesthesia (0-100%) from a syringe pump plugged into another Arduino.
This app was to be used by anesthesiologists during small, routine surgeries so that large rooms with expensive, bulky equipment did not have to be rented out for use. 

## Technical Info
We used a React app on the frontend, Flask to run the web server (in Python), and Arduino code (similar to C) to read in data and trasmit to the Raspberry Pi via HTTP.

## Images
![image](https://github.com/jpohlabel/portfolio/assets/113477103/0639c823-205d-4559-bbf1-edcbe72471fd)
