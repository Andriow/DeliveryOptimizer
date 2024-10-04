# DeliveryOptimizer

## Description
**DeliveryOptimizer** is a project developed to optimize delivery logistics using clustering techniques. The goal is to group deliveries efficiently, reducing the time and cost of logistics operations.

## Features
- **Data Analysis**: Import and analyze delivery data.
- **Clustering**: Group deliveries using the MiniSom model (Self-Organizing Maps).
  - **MiniSom**: MiniSom is a Python implementation of Self-Organizing Maps (SOM), an unsupervised learning technique that maps high-dimensional data into a lower-dimensional space while preserving the data topology. This is useful for identifying patterns and forming clusters of deliveries with similar characteristics.
- **Visualization**: Generate charts and maps to visualize clusters and optimized routes.
- **Route Optimization**: Implement algorithms to find the most efficient routes within each cluster.

## Requirements
- Python 3.x
- Jupyter Notebook
- Python Libraries: pandas, numpy, minisom, matplotlib, seaborn

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Andriow/DeliveryOptimizer.git
    ```
2. Navigate to the project directory:
    ```bash
    cd DeliveryOptimizer
    ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Open Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Navigate to the `ClusterFrete.ipynb` file and run all cells to view the analysis and optimization of deliveries.

## Contribution
Contributions are welcome! Feel free to open issues and pull requests.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
