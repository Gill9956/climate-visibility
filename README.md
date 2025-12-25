
# Visibility distance prediction

## Problem Statement :-

The objective of this project is to develop a machine learning model that can accurately predict the maximum visibility distance in a given location and weather condition. The model should take into account various weather parameters such as humidity, temperature, wind speed, and atmospheric pressure, as well as geographical features such as elevation, terrain, and land cover. The model should be trained on a large dataset of historical weather and visibility data, and validated using a separate test dataset. The ultimate goal is to provide a tool that can help improve safety and efficiency in various applications such as aviation, transportation, and outdoor activities.


## Tech Stack Used

1. Python
2. FastAPI
3. Machine learning algorithms
4. MongoDB

## How to run

Before you run this project make sure you have MongoDB Atlas account and you have the shipping dataset into it.

Step 1. Cloning the repository.

```

git clone https://github.com/Machine-Learning-01/Customer_segmentation.git

```

Step 2. Create a  environment.

```

Step 3. Install the requirements

```

pip install -r requirements.txt

```

Step 4. Export the environment variable

export MONGODB_URL= <MONGODB_URL>


```

Step 5. Run the application server

```

python app.py

```

Step 6. Train application

```bash

http://localhost:5000/train

```

Step 7. Prediction application

```bash

http://localhost:5000/predict

```




**Components** : Contains all components of Machine Learning Project

- Data Ingestion
- Data Validation
- Data Transformation
- Data Clustering
- Model Trainer
- Model Evaluation



## Conclusion

- This Project can be used in real-life by Users.
