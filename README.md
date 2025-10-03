# Airbnb Data Analysis Environment Setup

### Environment Details:
- **Python Version**: 3.13.1
- **Environment Type**: Virtual Environment (.venv)
- **Location**: `d:\Airbnb_Data_Analysis\.venv`

### Installed Packages:
- pandas (data manipulation)
- numpy (numerical computing)
- matplotlib (plotting)
- seaborn (statistical visualization)
- plotly (interactive plots)
- openpyxl (Excel file reading)
- jupyter (notebook environment)
- ipykernel (Jupyter kernel)

### How to Run Your Analysis:

#### Option 1: Using the Batch File (Easiest)
Double-click on `start_analysis.bat` in your project folder

#### Option 2: Manual Steps
1. Open PowerShell/Command Prompt
2. Navigate to your project folder:
   ```
   cd "d:\Airbnb_Data_Analysis"
   ```
3. Activate the virtual environment:
   ```
   .venv\Scripts\activate
   ```
4. Start Jupyter Notebook:
   ```
   python -m jupyter notebook
   ```

#### Option 3: Using VS Code
The notebook is already configured to use the virtual environment kernel, so you can run it directly in VS Code.

### Next Steps:
1. **Jupyter Notebook is currently running** - you should see it opening in your browser
2. Open `Airbnb_Data_Analysis.ipynb` 
3. Make sure your Excel file `1730285881-Airbnb_Open_Data.xlsx` is in the same folder
4. Run the cells one by one to see the analysis results

### Files Created:
- `requirements.txt` - For future package installations
- `start_analysis.bat` - Easy startup script
- `README.md` - This instruction file

### Troubleshooting:
- If you get import errors, make sure the virtual environment is activated
- If Excel file is not found, check the file path in the notebook
- If plots don't show, try running `%matplotlib inline` in a cell

Happy analyzing! 📊✨
