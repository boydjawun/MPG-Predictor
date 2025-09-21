# MPG Predictor
Fuel Efficiency Prediction with PyTorch Neural Network
Overview
This repository implements a simple feedforward neural network using PyTorch to predict car fuel efficiency (Miles Per Gallon, MPG) based on the Auto MPG dataset from the UCI Machine Learning Repository. The project demonstrates end-to-end machine learning workflow, including data loading, preprocessing, model training, evaluation, and inference on new data points.
Features /n
•  Data Preprocessing: Loads the dataset via URL, handles missing values, splits into train/test sets (80/20), standardizes numerical features (Cylinders, Displacement, Horsepower, Weight, Acceleration), bucketizes Model Year into discrete categories ([73, 76, 79]), and one-hot encodes the categorical Origin feature (USA=1, Europe=2, Japan=3).
•  Model Architecture: A multi-layer perceptron with an input layer matching the feature size, two hidden layers (8 and 4 units) with ReLU activations, and a single output neuron for regression.
•  Training: Uses Mean Squared Error (MSE) loss, Stochastic Gradient Descent (SGD) optimizer with learning rate 0.001, batch size 8, and trains for 200 epochs with loss logging every 20 epochs.
•  Evaluation: Computes MSE and Mean Absolute Error (MAE) on the test set.
•  Inference: Preprocesses and predicts MPG for new car data in the same format.

<img width="1509" height="856" alt="Screenshot 2025-08-04 161453" src="https://github.com/user-attachments/assets/531c61ad-514e-4f52-bd61-c83bec42adf9" />
<img width="1505" height="849" alt="Screenshot 2025-08-04 161554" src="https://github.com/user-attachments/assets/f7a069e9-2e97-4e34-9296-999140c7302b" />
<img width="1508" height="858" alt="Screenshot 2025-08-04 161626" src="https://github.com/user-attachments/assets/a5dbd15f-9022-4876-a2c6-400e4e1f9973" />
<img width="1508" height="854" alt="Screenshot 2025-08-04 161644" src="https://github.com/user-attachments/assets/63e7c228-cfb1-4f4b-a3b8-ec3b1efc5ec0" />
<img width="1494" height="263" alt="Screenshot 2025-08-04 161711" src="https://github.com/user-attachments/assets/bb6d1616-ec17-4f5a-8962-73fbc02512b2" />
<img width="1506" height="854" alt="Screenshot 2025-08-04 161739" src="https://github.com/user-attachments/assets/7bbd7c08-f50b-49f2-8ed3-4be923a2308e" />
<img width="1507" height="834" alt="Screenshot 2025-08-04 161755" src="https://github.com/user-attachments/assets/059f05bf-9712-40fb-b232-fda961d2ae83" />
