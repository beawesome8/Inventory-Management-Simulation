# Inventory-Management-Simulation

This project performs a Monte Carlo simulation for inventory management. It simulates the daily demand for products, calculates holding and shortage costs, and evaluates the performance of different suppliers based on their delivery times.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Parameters](#parameters)
- [Simulation Function](#simulation-function)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   
   git clone https://github.com/your-username/Inventory-Management-Simulation.git
   cd Inventory-Management-Simulation

2. Create and activate a virtual environment:

- python -m venv env
- source env/Scripts/activate  # On Windows
- source env/bin/activate    # On macOS/Linux

4. Install the required packages

   pip install -r requirements.txt

## Usage

1. Open the Jupyter Notebook

2. Open the Code.ipynb file and run the cells to perform the simulation.

## Parameters

- num_simulations: Number of simulations to run for each supplier.

- num_days: Number of days to simulate in each simulation.

- mean_demand: Mean daily demand for the product.

- std_demand: Standard deviation of the daily demand.

- daily_holding_cost: Cost of holding one unit of inventory per day.

- daily_shortage_cost: Cost of shortage per unit per day.

- delivery_time: Dictionary containing the delivery times for different suppliers.

## Simulation Function

The run_simulation function performs a single simulation for a given delivery time. It calculates the total holding and shortage costs over the simulation period.

## Results 

The results of the simulations are stored in a pandas DataFrame and displayed using the head() method. The DataFrame contains the following columns:

Supplier: The supplier being evaluated.

Simulation: The simulation number.

Total Holding Cost: The total holding cost for the simulation.

Total Shortage Cost: The total shortage cost for the simulation.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License 

This project is licensed under the MIT License. See the LICENSE file for details.
