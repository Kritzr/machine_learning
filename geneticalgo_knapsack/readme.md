# Genetic Algorithm for the Knapsack Problem

## 📌 Overview
This project implements a Genetic Algorithm (GA) to solve the **0/1 Knapsack Problem**. The algorithm optimizes the selection of items within a given weight limit to maximize the total value. The solution evolves over generations using **selection, crossover, and mutation**.

## 🚀 Features
- **Genetic Algorithm Implementation**: Uses random population generation, selection, crossover, and mutation.
- **Dynamic Input Handling**: Users provide item details and algorithm parameters.
- **Visualization**:
  - **Line Plot**: Tracks fitness evolution over generations.
  - **Scatter Plot**: Shows how fitness varies across generations.
  - **Box Plot**: Displays distribution of fitness scores.

## 🛠️ Requirements
Ensure you have the following installed:
- Python 3.x
- NumPy
- Matplotlib

To install dependencies, run:
```sh
pip install numpy matplotlib
```

## 📌 Usage
1. Run the script:
   ```sh
   python knapsack_ga.py
   ```
2. Enter the number of items and their weights/values.
3. Provide genetic algorithm parameters:
   - **Maximum Knapsack Weight**
   - **Crossover Rate**
   - **Mutation Rate**
   - **Reproduction Rate**
4. The algorithm runs and displays the best solution with its fitness.
5. Visualizations show the evolution of solutions over generations.

## 📊 Visualizations
- **Line Plot**: Shows the average fitness of the population over generations.
- **Scatter Plot**: Highlights individual fitness values per generation.
- **Box Plot**: Summarizes the spread and median of fitness scores.

## 🎯 Example Output
```
Enter number of items: 5
Enter name for item 1: Gold
Enter weight for Gold: 3
Enter value for Gold: 10
...
Best solution: [1, 0, 1, 1] Fitness: 35
```
Visualizations will be displayed in pop-up windows.

## 📜 License
This project is open-source and available under the MIT License.

## 💡 Future Improvements
- Implement **elitism** to preserve top solutions.
- Add **multiple crossover techniques**.
- Introduce **real-time visualization updates**.

## 👨‍💻 Author
Krithika

---
Happy Coding! 🎯

