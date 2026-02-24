# Project-2: Concrete Mix Designs
## Project Overview
This project invoved the modernization of Nebraska Department of Transportation's (NDOT) concrete mix design by transforming the existing Excel-based formulas into an input system in a python code. The resulting notebook automates the Absolute Volume Method, replacing the manual spreadsheet entry with a structured program designed for precision and accuracy. By fixing the calculation logic in Python, the system avoids broken cell errors than can be caused by misinputs in excel. 
## Technical Features
 - Modular Logic: The system separates complex mix design formulas - such as water weight calculations and volumetric yield - into independent Python functions. 
 - Pre-Loaded NDOT Scenarios: To offer some additional efficiency, the program includes four pre-validated mix profiles: Standard Paving (47B), Bridge Deck (47BD), Optimized Aggregates (47BR), and High Early Strength (PR3)
 - Sequential Workflow: The notebook guides users through the design process in a logical order that is comparable to the NDOT submittal sheets. This includes the project identification, material weights, and specific gravities.
 - Professional Reporting: After completion, the notebook generates a formatted chart for one cubic yard of concrete. This provides contractors and engineers with organized data for analyzing.
## Operation Guide
 - System Launch: Launch the Jupyter notebook in a compatible python environment.
 - Selection: Users select one of the four Pre-defined scenarios (1-4) or manual entry (5).
 - Data Entry: Enter the information corresponding to the prompt when given (project number, material weight, specific gravity, etc)
 - Report Generation: The system calculates water weight and aggregate weights before displaying an organized chart of information.
