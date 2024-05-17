# Graph Visualization from Adjacency Matrix


This project converts an adjacency matrix stored in a CSV file to a graph visualization using Python, NetworkX, and Pyvis. The visualization shows the nodes and edges of the graph with labels, and allows for interactive exploration of the graph.

## Prerequisites

Before running the script, ensure you have the following Python packages installed:
- pandas
- networkx
- pyvis

You can install these packages using pip:

```sh
pip install pandas networkx pyvis
```

## Usage

1. **Prepare the Adjacency Matrix CSV File**:
   - Ensure your CSV file (`adj_matrix.csv`) contains the adjacency matrix without a header row. Each cell should contain either 0 or 1, indicating the absence or presence of an edge, respectively.

2. **Modify and Run the Script**:
   - Use the provided Python script to read the CSV file, convert the adjacency matrix to an edge list, and visualize the graph. 

3. **Run the Script**:
   - Execute the script in your Python environment. This will read the adjacency matrix from `adj_matrix.csv`, convert it to a graph, and create an interactive visualization saved as `result.html`.

```sh
python visualize_graph.py
```

4. **View the Visualization**:
   - Open `result.html` in your web browser to explore the graph interactively.

## Notes

- The script generates a unique color for each node using the `generate_color` function.
- The nodes are arranged in a circular layout, and the physics of the network visualization is disabled for a fixed layout.
- The Pyvis visualization includes interactive menus for customizing the display of nodes, edges, and physics settings.

Feel free to customize the script further to fit your specific needs.