# Heterogeneous Consumers, Firm Competition and the Data Value Chain: An Agent-based Approach

## Game-theoretical Analysis

### Equilibrium Search

"Game_Julia01.ipynb" (Julia version: 1.4.1)

### Nash Equilibrium Analysis

"Game_Equil01.ipynb", "Game_Equil02.ipynb" (Python version: 3.10.12)

## Agent-based Simulations

### Firm Dynamics

"Firm_dynamics.ipynb" (Python version: 3.10.12)

### Results Analysis

"Simul_Analysis01.ipynb", "Simul_Analysis02.ipynb",
"Wilcoxon Signed Rank Test.ipynb" (Python version: 3.10.12)

## Project Structure

```
Heterog_Consumers_DVC/
├── Game_Julia01.ipynb              # Equilibrium search using Julia
├── Game_Equil01.ipynb              # Nash equilibrium analysis (Python)
├── Game_Equil02.ipynb              # Nash equilibrium analysis (Python)
├── Firm_dynamics.ipynb             # Agent-based firm dynamics simulation
├── Simul_Analysis01.ipynb          # Simulation results analysis
├── Simul_Analysis02.ipynb          # Simulation results analysis
├── Wilcoxon Signed Rank Test.ipynb # Statistical testing of simulation results
├── rand_sample03_new_100.csv       # Sample data for consumer taste distribution (functionality; data restriction)
├── requirements_Julia.txt          # Julia package dependencies
├── requirements_Python.txt         # Python package dependencies
```

## Requirements

### Julia Packages

- **Distributions.jl** - Probability distributions and statistical functions
- **MvNormalCDF.jl** - Multivariate normal cumulative distribution functions
- **Query.jl** - Data manipulation and querying operations
- **Plots.jl** - Visualization and plotting framework
- **StatsPlots.jl** - Statistical plotting recipes and visualizations
- **DataFrames.jl** - Tabular data structures and operations
- **CSV.jl** - Reading and writing CSV files
- **StatsBase.jl** - Basic statistical functions and utilities
- **Random** (stdlib) - Random number generation
- **Dates** (stdlib) - Date and time operations

### Python Packages

- **numpy** - Array operations and numerical computing
- **pandas** - Data manipulation and analysis with DataFrames
- **matplotlib** - Data visualization and plotting
- **seaborn** - Statistical data visualization
- **scipy** - Scientific computing (optimization, linear algebra, statistics, interpolation)
- **numba** - Just-in-time compilation for performance optimization
- **ipywidgets** - Interactive widgets for Jupyter notebooks

## Acknowledgments

This work has received funding from the European Union's Horizon 2020 research and innovation programme under the Marie Skłodowska-Curie grant agreement No 956107, "Economic Policy in Complex Environments (EPOC)". Many thanks for the guidance of Prof. Herbert Dawid (UNIBI), Prof. Domenico Delli Gatti (UCSC) and Prof. Christiane Fuchs (UNIBI).
