Automated Irrigation and weather prediction system

Problem statement
Varying soil moisture due to unpredictable weather causing crop damage.

Abstract
•	According to THE Central Ground Water Board, in 2009, Odisha’s groundwater volume was assessed at 16.69 billion cubic metres. It had dropped to 15.57 billion cubic metre in 2017. The declination indicates scarcity of irrigation water for crops in the upcoming decades.

•	In India, around 36 mha agricultural area was affected due to unpredictable hydro-meteorological calamities, including heavy rain and floods since 2016 – 6.65 mha in 2016, 5.08 mha in 2017, 1.70 mha in 2018, 11.42 mha in 2019, 6.65 mha in 2020 and 5.04 mha in 2021. 

•	Overall crop damage affects the state GDP of Odisha.  Cyclones and floods occurring almost every year in Odisha affects the growth rate to fall by 1.8-4% , in comparison to a high growth rates in non-cyclonic seasons.

•	Apart from losses to life and property, natural disasters also lead to crop failure, decline in surface and groundwater level, increasing unemployment and under-employment, migration, and indebtedness.


Solution statement

•	Designing a reliable system for predicting amount of rainfall for a range of months.

•	Predict upcoming cyclonic storms using data visualization from the predicted range of values.

•	Monitoring moisture content in different type of soil and at different depths using IOT devices and ensuring sustainable water management for crops.



Approach

•	Fetching rainfall data from 1994 up to 2021 and using a SARIMAX model for predicting the amount of rainfall in the upcoming months using machine learning.

o	Used 300 data points for training and 36 for testing the model. The model shows an accuracy of -- %

o	Used two models – ARIMA and SARIMAX for predicting the results. ARIMA showed a much lower accuracy than SARIMAX due to the rainfall dataset being seasonal in nature.

o	There are outliers in years of 1999,2016,2017,2019,2020,2021 due to cyclonic storms happening in the coastal regions of Odisha.


o	A graph of year to rain (in mm) is plotted for final visualization.

•	Using Arduino/Uno and Soil hygrometer to measure moisture content in soil and obtaining information about the amount of water stored in the soil horizon. After the Arduino detects moisture percentage crossing a threshold value, the water pumping starts automatically for that part of soil. 



Group members and contact numbers
Group Link: https://chat.whatsapp.com/IEkikOnDEjMFjTW71MmvWE

1.	Rajat Pati (Team Lead)
2.	Pratik Das
3.	Randhir Raj 
4.	Shreya Srivastava 
5.	Ayush Kumar 
6.	Ankit Kumar 
7.	Sriram Kumar 
8.	Arjyabrat digdarshan
9.	Sanskar Mohanty 
10.	Rajat Moharana 
11.	Biswaranjan Das
12.	K. GURUCHARAN REDDY
13.	OMKAR ASHUTOSH MOHAPATRA:
14.	AISHWARIYA ABHISARIKA
15.	MANASI PANDA
16.	SHARMISTHA DAS 
17.	Shuvalaxmi Nanda
18.	Aurosheekha Senapati
19.	Ayushman narayan nath
20.	Team Swadhin (For IoT project)


Tasks assigned
      
•	Dataset Collection and cleaning – Rajat Pati, Pratik Das
•	Model training and prediction – Rajat Pati
•	IOT and Arduino – Team Swadhin 
•	Front-end group: 
Team lead: - Manasi Panda
i.	Omkar Ashutosh Mohapatra 
ii.	K Guru Charan Reddy
iii.	Ayiswariya Abhisarika
iv.	Sharmistha Das
v.	Shuvalaxmi Nanda

•	Rainfall prediction API:
Team lead: - Randhir Raj 
i.	Ayush Kumar 
ii.	Biswaranjan Das
iii.	Sriram Kumar
iv.	Ankit kumar
v.	Shreya Srivastava


•	Rainfall Analysis API:
Team lead:-  Sanskar Mohanty
i.	Arjyabrat Digdarshan
ii.	Rajat Moharana
iii.	Ayushman Narayan Nath
iv.	Aurosheekha Senapati



