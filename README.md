# Customer Segmentation EDA

## Overview
This project involves performing an Exploratory Data Analysis (EDA) on a customer dataset to identify and understand different customer segments based on their purchasing behavior. The dataset used for this analysis is the Mall Customers dataset, which contains demographic information about customers along with their annual income and spending scores.

## Dataset
The dataset used in this project is the Mall Customers dataset, which can be downloaded from [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

### Features
- **CustomerID**: Unique ID for each customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature

## Project Structure
The repository contains the following files and directories:
- `data/`: Directory containing the dataset
  - `Mall_Customers.csv`: The dataset file
- `Customer_Segmentation_EDA.ipynb`: Jupyter Notebook with the complete EDA process
- `README.md`: This file

## Steps and Analysis

### 1. Data Loading and Exploration
- Load the dataset and display the first few rows
- Summarize the dataset to understand the basic statistics
- Check for missing values in the dataset

### 2. Data Visualization
- Plot the distributions of numerical features (Age, Annual Income, Spending Score)
- Visualize relationships between features using pairplots
- Create a correlation matrix to understand the correlations between features

### 3. Clustering for Customer Segmentation
- Apply K-means clustering to segment customers based on their Age, Annual Income, and Spending Score
- Visualize the resulting clusters to understand the different customer segments

## Visualizations
The project includes several visualizations to aid in the understanding of the data:
- **Histograms**: To visualize the distribution of Age, Annual Income, and Spending Score
- **Pairplot**: To visualize relationships between features
- **Correlation Matrix**: To visualize correlations between features
- **Cluster Plot**: To visualize the customer segments identified by K-means clustering

## How to Run the Notebook
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/Customer_Segmentation_EDA.git
    cd Customer_Segmentation_EDA
    ```

2. **Install Required Libraries**:
    Ensure you have the required Python libraries installed. You can install them using pip:
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3. **Open the Jupyter Notebook**:
    Start Jupyter Notebook and open `Customer_Segmentation_EDA.ipynb` to run the analysis step-by-step.

## Contributing
Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue to discuss.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- The dataset used in this project is available on [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

## Author
- Ivy Qwinn
