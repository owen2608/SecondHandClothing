# AI Price Fairness Estimator

This project contains a Jupyter notebook that implements an AI-powered price fairness estimator for Vinted marketplace data.

## Prerequisites

- Python 3.8 or higher
- pip package manager

## Setup Instructions

### 1. Install Dependencies

First, install the required Python packages:

```bash
pip install -r requirements.txt
```

### 2. Environment Configuration

The project includes a `.env` file with pre-configured settings. No additional configuration is needed for basic usage.

### 3. Running the Jupyter Notebook

#### Option 1: Using Jupyter Notebook (Classic Interface)

```bash
jupyter notebook
```

This will:
- Start the Jupyter server on `localhost:8888` (default)
- Open your web browser automatically
- Display the project directory

Click on `AI_Price_Fairness_Estimator.ipynb` to open the notebook.

#### Option 2: Using JupyterLab (Modern Interface)

```bash
jupyter lab
```

This provides a more modern interface with the same functionality.

#### Option 3: Specify Custom Port

If port 8888 is already in use:

```bash
jupyter notebook --port 8889
```

### 4. Running the Notebook

1. Open `AI_Price_Fairness_Estimator.ipynb`
2. Run all cells sequentially using:
   - **Shift + Enter** to run each cell individually
   - **Cell > Run All** to execute all cells at once
   - **Kernel > Restart & Run All** to restart and run everything fresh

## Project Structure

- `AI_Price_Fairness_Estimator.ipynb` - Main analysis notebook
- `vinted_data.csv` - Dataset file
- `requirements.txt` - Python dependencies
- `.env` - Configuration settings

## Data

The notebook analyzes Vinted marketplace data (`vinted_data.csv`) to estimate fair pricing using machine learning techniques.

## Troubleshooting

### Common Issues

1. **Port already in use**: Use a different port with `--port` flag
2. **Missing dependencies**: Run `pip install -r requirements.txt`
3. **Python version**: Ensure Python 3.8+ is installed

### Stopping the Server

- Press `Ctrl+C` in the terminal where Jupyter is running
- Confirm with `y` when prompted

## Additional Notes

- The notebook includes data analysis, machine learning model training, and price fairness assessment
- All configuration is handled through the `.env` file
- Results and visualizations will appear inline within the notebook