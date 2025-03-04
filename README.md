==>Project Overview
1. This project is a Real Estate Price Predictor that estimates house prices based on input details like area, bedrooms, and age.
2. The data is taken from Kaggle's real estate dataset and processed before being used for training.
3. The model is built using brain.js, a JavaScript library for neural networks, to predict house prices.
4. The processed data and trained model are stored in local storage, so they don’t have to be downloaded again.


==>How to Run Locally
1. Open the project in a browser (Chrome, Edge, etc.).
2. The application automatically loads the saved model and data from local storage; otherwise, it fetches and processes the data from the CSV file.


==> Features & Technologies Used
1. Data Handling: The app reads a CSV file containing real estate prices and processes it.
2. Data Preprocessing: It removes incomplete or invalid entries before training the model.
3. Model Training: Uses brain.js to create and train a neural network with the cleaned data.
4. Model Saving: The trained model is stored in local storage so it doesn’t have to be retrained every time.
5. User Input Form: Users enter property details like size, number of bedrooms, and location.
6. Form Validation: Ensures only valid numbers and text are entered before making predictions.
7. Prediction: Once the user submits the details, the trained model estimates the house price.
8. Data Normalization: The app scales data values (e.g., area, bedrooms) so the neural network can process them efficiently.
9. Visualization: Uses Recharts to show actual vs. predicted prices in a line chart.
10. Dynamic Data Storage: Stores and reuses preprocessed data and trained models in local storage.
11. Error Handling: If data is missing or incorrect, the app logs warnings instead of crashing.
12. Responsive Design: Adjusts layout for mobile, tablet, and desktop users.
13. Modern UI: Features a clean and visually appealing interface with an image preview.
14. Optimized Training: The neural network runs for 5000 iterations, improving accuracy over time.