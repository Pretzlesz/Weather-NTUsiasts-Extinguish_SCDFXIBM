# Weather-NTUsiasts-Extinguish_SCDFXIBM
Use of IoT and AI to predict flash floods and vegetation fires
---

## Problem

Due to global warming, climate change has become more rapid, causing a rising trend of vegetation fires and flash floods in Singapore. In 2019,there were 883 cases of vegetation fires and a significant number of cases of flash floods. As a result of the seriousness of this situation, there could potentially be a lot of damage caused to infrastructure and lives. Hence, to mitigate the impacts of these weather events, it will be helpful for SCDF to be better prepared for these emergencies by implementing solutions and measures to predict and address them early so that any damage to infrastructure or threats to lives will be minimised.

---
## Solution
To help SCDF and the government better prepare for and react to various threats posed by these extreme weather events, we propose our solution “Extinguish”. Our solution aims to predict flash floods and vegetation fire locations through use of  the IoT platform on IBM Cloud to collect weather data. Through the use of AI like IBM Watson and data analytics methods, predictions about vegetation fires and flash floods can be made. 

Our solution “Extinguish” consists of:

1.Use of IoT Platform on IBM cloud to collect weather data 

2.Use of supervised machine learning models to predict extreme weather incidents like vegetation fires which are caused by hot and dry weather and flash floods which occur due to excessive rainfall. These could be done on IBM watson which has Jupyter notebooks to run our models and visualize our data. To train the machine learning model, we can make use of the weather data that is made available in government websites. 

This solution would help SCDF to optimize resources better. Through the implementation of our solution, the SCDF would be able to pinpoint hotspots and detect any weather events in these areas early. With early detection, SCDF will be able to cut down on resources such as manpower and cost incurred into tackling the problem. Thus, these resources can be better allocated into other areas, which would help to improve SCDF’s overall efficiency. 

Extinguish’s reliability can be limited as it heavily depends on the accuracy and availability of data. However, this can be resolved by implementation of more IoT devices in hotspots and preprocessing the data.





---
## Architecture of Proposed Solution
![image](https://user-images.githubusercontent.com/70022847/121149438-3f14f900-c875-11eb-9d76-924edace2466.png)
1. The **IoT Devices** such as *Rain Sensors* and *Temperature Sensors* will measure the relevant weather data like *humidity* and *temperature*
2. The raw data collected will then be transferred and stored in **IBM Cloud** which will be organised and preprocessed
3. The processed data will be passed into both the **Data Analytics** software for *Data Visualisation* and the **Machine Learning Model** for *prediction of future extreme weather events*
4. These results will then be fed into the **SCDF database** which can be accessed to better understand which periods of time will have the extreme weather events like *vegetation fires* and *flash floods* and they can be on standby to combat them
---

















---
## Product Roadmap
![image](https://user-images.githubusercontent.com/70022847/121058581-10563e80-c7f3-11eb-826b-192366df737c.png)
---

## Getting Started
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
 




