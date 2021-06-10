# Weather-NTUsiasts-Extinguish_SCDFXIBM
### Use of IoT and AI to predict flash floods and vegetation fires

---
## Team Description

Hello, We are the **Weather NTUsiasts!**
| Role | Name |
| ----------- | ----------- |
| Leader | Pritika Nandakumar |
| Designer | Sankpal Shibani Prashant |
| Coder | Parameswaran Varshini |
| Engineer | Stanley Wong Qi Ren |
| Researcher | Wong Ming Yuan Delvin |

---
## Problem Statement
How might we leverage technology to better predict and prepare for the foreseeably higher frequency and greater severity of extreme weather events and natural disasters?

---
## Problem

Climate change has profound impacts on the environment, resulting in the rising trend of vegetation fires and flash floods in Singapore. In 2019,there were 761 cases of vegetation fires and 2 incidents of severe flash floods. Vegetation fires and flash floods can cause widespread and irreparable damage on the environment, infrastructure, and even our lives. Therefore, SCDF must evolve from traditional reactive measures, to predictive solutions in order to stop a fire or a flood before it happens. That is the only way to mitigate the harmful impacts of severe weather events on our environment and our livelihood. 

---
## Solution

Our solution "Extinguish" aims to predict extreme weather events, allowing SCDF to take preventive or early detection measures. Through the use of the IoT platform on IBM cloud to collect weather data, together with AI (IBM Watson), and data analytics, this model aims to provide accurate predictions of flash flood and vegetation fire "high-risk zones".

Our solution “Extinguish” consists of:

1.Use of IoT Platform on IBM cloud to collect weather data 

2.Use of supervised machine learning models to predict extreme weather incidents like vegetation fires which are caused by hot and dry weather and flash floods which occur due to excessive rainfall. These could be done on IBM watson which has Jupyter notebooks to run our models and visualize our data. To train the machine learning model, we can make use of the weather data that is made available in government websites. 

This solution would help SCDF to optimize resources better. Through the implementation of our solution, the SCDF would be able to pinpoint "high-risk" zones and detect any weather events in these areas early. With early detection, SCDF will be able to cut down on resources such as manpower and cost incurred into tackling the problem. Thus, these resources can be better allocated into other areas, which would help to improve SCDF’s overall efficiency. 

Further into the development pipeline, we aim to include the use of Unmanned Aerial Vehicles (UAVs) and computer vision to quickly and efficiently patrol "high-risk zones" to identify fire and smoke, or flooding chokepoints.

---
## Pitch Video
https://www.youtube.com/watch?v=pzz3_G-sQgc&ab_channel=DelvinWong






---
## Architecture of Proposed Solution!
![image](https://user-images.githubusercontent.com/70022847/121541541-fa868a80-ca39-11eb-9922-baeb800b9622.png)
1. The **IoT Devices** such as *Rain Sensors* and *Temperature Sensors* will measure the relevant weather data like *humidity* and *temperature*
2. The raw data collected will then be transferred and stored in **IBM Cloud** which will be organised and preprocessed
3. The processed data will be passed into both the **Data Analytics** software for *Data Visualisation* and the **Machine Learning Model** for *prediction of future extreme weather events*
4. These results will then be fed into the **SCDF database** which can be accessed to better understand which periods of time will have the extreme weather events like *vegetation fires* and *flash floods* and they can be on standby to combat them
5. These data can be used in conjunction with **UAVs** and **Computer Vision** to track signs of vegetation fires across the country

---
## Hyperlink of Detailed Solution
https://docs.google.com/document/d/1yNR_p6dWVKf_hQl3nRReH02Lw2fBV8vpv2BMBddqBcA/edit


---
## Product Roadmap
![image](https://user-images.githubusercontent.com/70022847/121058581-10563e80-c7f3-11eb-826b-192366df737c.png)
---

## Getting Started
---
### IoT
In IBM Watson IoT Platform dashboard, select Apps (a), then Generate API Key (b). Kindly save the generated API key and Authentication token. Once lost you need to generate again.

Select the IBM IoT App In node, in Authentication (a) select API Key. Then In the API Key, click on the pen (b), to create a new API key. Then enter the Device Id (c).
Next enter the API Key (a) and API token (b) saved earlier. Click update and Deploy to save the settings.

Select the IBM IoT App Out node, in the Authentication, select API Key, then in the API Key select the previously created API Key in IBM IoT App In node. Then key in the Device Id (b). Click update and Deploy to save the settings.
 
 ---
### IBM Watson and Jupyter Notebook
1.Open Project in Watson Studio.

2.View notebooks

3.Find data files from data assets and Jupyter notebooks from notebooks under assets 

---
## Platforms used to build solution
IBM Cloud

IBM Watson Studio

IBM Watson IoT Platform studio

Jupyter NoteBook

Python
 




