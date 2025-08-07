# Documentation

This directory contains the HTML documentation for the Motor Protein Transport Simulation project.

## Files

- **`index.html`** - Main documentation landing page with project overview
- **`motorprotein_simulation.html`** - Complete Jupyter notebook converted to HTML format

## Viewing the Documentation

### Option 1: Open Locally
Navigate to this directory and open `index.html` in your web browser to view the documentation.

### Option 2: Using Python HTTP Server
You can serve the documentation locally using Python:

```bash
# From the docs directory
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

### Option 3: Using VS Code
You can use the "Live Server" extension in VS Code to serve the documentation.

## About the Notebook

The `motorprotein_simulation.html` file contains the complete simulation notebook with:

- Theoretical background and mathematical derivations
- Numerical implementation of random walk simulations
- Comprehensive analysis and visualization of results
- Comparison between numerical and analytical solutions
- Parameter sensitivity studies

The notebook is fully self-contained with all plots, equations, and explanations embedded in the HTML file.

## Technical Details

- **Generated from**: `notebooks/motorprotein_simulation.ipynb`
- **Conversion tool**: Jupyter nbconvert
- **Format**: Standalone HTML with embedded assets
- **File size**: ~3MB (includes all plots and formatting)

---

*This documentation was automatically generated as part of the Motor Protein Transport Simulation project.*
