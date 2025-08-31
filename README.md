# DAG Generator

This project generates a Directed Acyclic Graph (DAG) using Python, NetworkX, and Matplotlib.  
The script will create a random DAG and save it as an image (`dag.png`) in your project folder.

## 🚀 Features

- **Random Node Generation** – Assign nodes randomly into ranks.  
- **Adjacency List Construction** – Automatically generate DAG relationships.  
- **BFS Level Computation** – Determine node levels for hierarchical layouts.  
- **Visualization** – Render DAGs using **NetworkX** and **Matplotlib**.  
- **Export Graph** – Save the generated DAG as `dag.png`.  

## 🛠 Technologies Used

- Python  
- NetworkX  
- Matplotlib  
- Collections (deque)  

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/AmulyaVinceChemparathy/dag.git
cd dag

# 2. Install dependencies
pip install networkx matplotlib

# 3. Run the script
python dag_generator.py

# 4. View the generated DAG image in your project folder
# (dag.png will be created after running the script)
