# Pyseidon: Advanced Water Network Analysis and Simulation Library

Pyseidon is a comprehensive and flexible Python-based library designed for the analysis, simulation, 
and visualization of water distribution networks. Inspired by the powerful water deity of Greek mythology, 
this library provides insightful tools to help researchers and engineers efficiently model and interpret 
water flow patterns, demand patterns, and distribution system behaviour. 

Key Features:
- Flow pattern clustering using advanced KMeans and PCA analysis
- Gaussian Mixture Modeling (GMM) for identifying the optimal number of clusters
- Data manipulation capabilities including dataset splitting, merging, and saving
- Detailed summary statistics for comprehensive data analysis
- Powerful visualization tools for water demand and flow patterns
- Ability to run simulation models on a node from EPANET by integrating with WNTR

## Installation Requirements:

To install and use **Pyseidon**, you must ensure the following dependencies are installed in your environment:

### Python Version:
- Python 3.9 or earlier  
  **Note**: The **WNTR** library only supports Python 3.9 or earlier. Make sure your environment is configured accordingly.

### Required Libraries:
You can install the required Python packages using `pip`:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn scipy wntr

```

### WNTR Installation:

To run water network simulations using EPANET through **Pyseidon**, you need **WNTR** installed. You can install WNTR by running:

```bash
pip install wntr
```
Alternatively, you can use package managers such as HomeBrew to install WNTR.

### Cloning and Installation:

Clone the **Pyseidon** repository from GitHub:

```bash
git clone https://github.com/your-repo/pyseidon.git
```

### Navigate to the project directory and install the library:

```bash
cd pyseidon
pip install .
```
Once installed, you can start using Pyseidon for water demand analysis and simulations.


