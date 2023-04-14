# AGRGCN

Attention Based Gated Recurrent Graph Convolutional Network for Short-Term Traffic flow Forecasting

<img src="https://github.com/WhutWzh/MyPic/blob/main/AGRGCN.png?raw=true" alt="image"  />

## Dataset

**HW-ENG:** This traffic dataset contains specific traffic information, including average speed, traffic flow, sensor location, and date, collected from 222 detectors on the highway of England. The time granularity of the original traffic dataset is 15 minutes. Sensors are distributed on 12 roads, including M6, M60, M62, M67, and A556, which cover server cites that contain Manchester, Warrington, and Blackburn. The distribution of sensors of the dataset is presented in the following figure. A whole year of traffic data ranging from January 1st, 2019, to December 31st,2019, is used for the experiment. The total number of traffic data in the dataset is 15,472,512. To mine for hidden correlations among traffic flows at nearby observation points, we enhanced the dataset with topological road information based on the distance among sensors through Google Maps' service.

<img src="https://github.com/WhutWzh/MyPic/blob/main/dataSet-sensor-Distribution.png?raw=true" alt="image" style="zoom:50%;" />



​                               

