# Crop-Recommendation-System
Precision agriculture is currently trending, offering farmers the ability to make informed decisions about their farming strategies. This system was created by combining data on rainfall, climate, and fertilizer use available for Indian datasets. The model performs well in neighboring countries such as Nepal, Sri Lanka, Bhutan, and others Asian countries and other countries as well. Predicting suitable crops for farmers can significantly enhance land productivity and farming efficiency.

**How and whom does crop recommendation system benefits?**
**Farmers**: By providing them with data-driven insights, it helps farmers select the most suitable crops for their specific soil and climate conditions, leading to increased yields and improved farming efficiency.

**Agricultural Planners and Policymakers**: They can use the system to develop better agricultural strategies, optimize resource allocation, and implement sustainable farming practices.

**Agricultural Extension Services**: These services can offer more accurate and tailored advice to farmers, enhancing the overall support system.

**Researchers and Scientists**: The system provides a valuable tool for studying the relationships between soil properties, climate conditions, and crop yields, aiding in the development of innovative agricultural techniques.

**Environmental Conservationists**: By promoting optimal crop selection and resource use, the system can contribute to more sustainable agricultural practices, reducing environmental impact.

**Data fields**

**N** - ratio of Nitrogen content in soil

**P** - ratio of Phosphorous content in soil

**K** - ratio of Potassium content in soil

**temperature** - temperature in degree Celsius

**humidity** - relative humidity in %

**ph** - ph value of the soil

**rainfall** - rainfall in mm Based on this variables, we will try to predict crop recommendation system for farmers.


_I have implemented a Gaussian Naive Bayes machine learning model, achieving an accuracy of 99.5%. I plan to deploy this model using Flask and Heroku, making it accessible to farmers worldwide. This dataset is available in  Kaggle ._ https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset
