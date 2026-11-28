11/18/2026 (failed to save, restored on 11/19/2026)
Setup GitHub and began organizing parts list. 
Started initial designs and contacted Gifted and Talented coordinator to apply for grant (to afford materials). 

11/19/2026
Collected donations from friends and teachers--like an UNO R3 micro controller--to cover as much of the project as possible. 
Began collecting resources to learn key concepts such as voltage & amp draw of motor and RMP laws. 
First learned what a loadcell is, and found a cheap version from https://shillehtek.com/
Learned that the specific load cell gives an analogue signal (~5-10 mV) at full load, but Arduino can only provide 1-2 steps across 5kg range for analogue pins. 
Either have to use another more advanced micro-controller, or amplify and convert load cell signal. 
Choose ESP32 as new micro controller as a result. 
Currently 11:30 pm, finishing part list; ran into some small issues with back orders and voltage incompatibility. 

11/20/2026
Began creating paper drawings for CAD reference. 
Checking the availably of my libraries local 3d printer for the several 3d printed parts. 
Creating 1st base plate for printing, workshopping measurements.
Modeled some of the key components for easy conjunction in fusion assembly. 

11/21/2026
Uploaded several CAD designs to Github.
Still no updates on components order or grant. 
Counting work on final design.

11/22/2026
Learning what ESP32 drivers are and how SCL vs SDA work to send and receive data.
Programming demo version for ESP32 and MPU sensor in Wokwi.

11/23/2026
Programmed demo version for both MPU sensor and LoadCell in Wokwi.

11/24/2026
Researched specifications for motor, loadcell, and MPU sensor.
Designed and fabricated Motor/Sensor head plate at local makerspace.

11/25/2026
Missing, update later

11/26/2026
Learned and practiced with Google Colab, an open source platform for data analysis, not dissimilar to matplotlib.
Learned how to utilize pandas with python.

11/27/2026
Spent the day analyzing sample data from a real world MPU, focuses on acceleration.
Analyzed acceleration as a combined xyz scalar.
Used Peak-to-Peak, Crest Factor, Rolling Average, and Frequency Residuals to find anomolies and colleration within the data.
Finally created a program to complete a Fast Fourier Transform and find max amplitude corresponding frequency. 



