# Physik Site

A comprehensive computational physics repository exploring fundamental physics concepts through interactive Jupyter notebooks and Python scripts.

## Overview

This project is dedicated to helping learners and physics explorers understand complex concepts through computational methods and visualizations. We cover various aspects of physics, with a focus on computational approaches to physics problems.

## Project Structure

```
├── dirac_delta.ipynb          # Dirac delta function analysis and visualization
├── fourier_series.ipynb       # Fourier series decomposition and applications
├── fourier_n_laplace.ipynb    # Fourier and Laplace transform theory
├── gauss_plot.ipynb           # Gaussian distribution plots and analysis
├── error_in_prism_mu.ipynb    # Prism error analysis
├── resistor.ipynb             # Resistor circuit analysis
├── anish_dai.ipynb            # Additional physics concepts
├── ddf_from_exl.ipynb         # Data processing from Excel files
├── bg_rad.py                  # Background radiation calculations
├── bgrad1.py                  # Gradient-based computations
├── gaussplot.py               # Gaussian plotting utilities
├── pyxl_for_ddf.py            # Excel data processing utilities
├── main.py                    # Main entry point
├── data/                      # Experimental and analysis data
│   ├── inside_analysis.tsv
│   ├── inside.tsv
│   ├── outside_analysis.tsv
│   ├── outside.tsv
│   ├── pract.tsv
│   |── resistance_data.tsv
│   
└── figs/                      # Generated figures and plots
```

## Key Notebooks

- **dirac_delta.ipynb** - Explores the Dirac delta function with mathematical proofs and physical interpretations
- **Dirac_Delta_Simulation.ods** - Spreadsheet(Librecalc) file of same dirac delta notebook, with all the graphs plotted.
- **fourier_series.ipynb** - Comprehensive analysis of Fourier series and function decomposition
- **fourier_n_laplace.ipynb** - Advanced transforms and their applications in physics
- **resistor.ipynb** - Circuit analysis and resistance computations

## Installation

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab

### Setup

1. Clone the repository:
```bash
git clone https://github.com/adarsha121/physik-site.git
cd physik-site
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Running Notebooks

Launch Jupyter to explore interactive notebooks:
```bash
jupyter notebook
```

Then open any `.ipynb` file to view code, equations, and visualizations.

### Running Python Scripts

Execute standalone scripts:
```bash
python main.py
python demo.py
```

## Dependencies

See `pyproject.toml` for project configuration and dependencies.

## Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

## License

This project is open source and available for educational use.

## Authors

- Adarsha ([@adarsha121](https://github.com/adarsha121))

## Acknowledgments

This resource is created to support physics education through computational methods and hands-on exploration.
