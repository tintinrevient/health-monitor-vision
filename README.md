## Use Case
Wearable Health Devices (WHDs)的应用可以归为以下三类：
* 应用场景: Home/Remote + Clinical
* 监控类型: Online + Offline
* 用户类型: Healthy + Patient

![Classification](./images/sensors-18-02414-g001.jpg)

1. Activity - 可以运用BAM (Business Activity Monitoring)，监控实时状态，建立个人档案，分析不同个体的均值，从而在出现异常值时可以预警。
2. Prediction - 可以运用机器学习，基于历史数据，训练数据模型，用于预测未来异常，辅助医生诊断。
3. Anomaly Detection - 可以基于Online的实时监控或者Offline的数据模型，识别异常pattern，从而提供预警。
4. Diagnosis Support - 用于医生介入，比如预约医生。


## Vital Signs
实时监控指标，包括以下7个：
* BT (Body Temperature): 体温
* BP (Blood Pressure): 血压
* RR (Respiration Rate): 呼吸率
* BG (Blood Glucose): 血糖
* HR (Heart Rate): 心率
* SpO2 (Blood Oxygen Saturation): 血氧饱和度
* ECG (Electrocardiogram): 心电图

![Signs](./images/sensors-18-02414-g002.jpg)


## Generic Architecture

![Architecture](./images/sensors-18-02414-g003.jpg)


## One Example
1. SensoTRACK Ear Sensor
2. Google Contact Lens
3. BioPatch
4. Smartwatch Basis PEAK
5. QardioCore
6. Vital Jacket T-shirt
7. Moov (Activity Tracker)

![Architecture](./images/sensors-18-02414-g004.jpg)


## Trend of Wearable Health Devices

![Trend](./images/sensors-18-02414-g007.jpg)


## Telehealth World Market
* CHF (Congestive Heart Failures): 心肌梗塞 - 49%
* Diabetes: 糖尿病 - 19%
* Hypertension: 高压力 - 13%
* COPD (Chronic Obstructive Pulmonary Disease): 慢性阻塞性肺疾病 - 12%
* Mental Health: 心理疾病 - 3%
* Others: 其他 - 4%

![Market](./images/sensors-18-02414-g008.jpg)


## Technical Stack
* Streaming Engine: [Esper](http://www.espertech.com/esper/), [Apache Flink](https://flink.apache.org/), [Apache Spark](https://spark.apache.org/)
* Deep Learning: [TensorFlow](https://www.tensorflow.org/), [TFLearn](http://tflearn.org/), [Keras](https://keras.io/)
* Computer Vision: [OpenCV](https://opencv.org/)




## Reference
* [Wearable Health Devices—Vital Sign Monitoring, Systems and Technologies](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6111409/)
* [Chicago Police produce video to encourage officer to seek help](https://www.chicagotribune.com/news/breaking/116237042-132.html)
* [Mitchell Jeffrey - Critical Incident Stress Debriefing](http://www.info-trauma.org/flash/media-f/mitchellCriticalIncidentStressDebriefing.pdf)