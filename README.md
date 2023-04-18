# SafeSF

In the US, 42,000 traffic deaths and millions more injuries occur each year. 31% of the accidents occur in places where no other accidents happened nearby (within 50 meters) within four years. With prediction machine learning algorithms, our goal is to help reduce traffic accidents by providing a map visualization that warns our users if the road that they plan to take is classified as more dangerous than others.

This was achieved by predicting collisions by using features such as stop signs, street paving data, bus stops, road type, satellite images, zipcodes, and collision data. For more details please visit [SafeSF webpage](https://nbargo.wixsite.com/safesf).

# Recommendation

After experimenting with various model architectures, our team's recommends using the the Multinomial Logistic Regression model with weights defined in this repo. The model was observed to have the highest F1 score and addressed the class imbalance problem relatively better than other architectures. 

# Repo Structure

The repo contains source code from all the team members. The repository is split three sections:

- Data: The directory contains data used in the project.
- EDA: The directory contains jupyter notebooks showing exploratory data analysis as well as data pipelines.
- Models: The directory contains the recommended models as well as all the experiments done so far.

