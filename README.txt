README.txt — Wind Turbine Cost and Environmental Assessment – Isle of Ouessant
=======================================================================

Project title:
----------------
Wind Turbine Cost and Environmental Assessment – Isle of Ouessant

Objective:
----------------
This project presents a detailed comparative analysis of three wind turbine models—Alstom ECO122, Enercon E33, and Aventa AV7—for potential deployment on the Isle of Ouessant. The study evaluates energy yield, cost per kilowatt-hour (€/kWh), capital expenditure, and environmental impact to determine the most suitable turbine for sustainable energy generation in a protected natural environment.

-----------------------------------------------------------------------
Key Findings:
-----------------------------------------------------------------------
• Alstom ECO122: Highest energy yield, lowest cost per kWh (€0.0228), but very high capital cost (€6.58M) and large visual impact (89 m hub height).
• Enercon E33: Balanced trade-off between cost (€2.6M), efficiency (€0.0371 /kWh), and low environmental footprint (37 m hub height).
• Aventa AV7: Low unit cost but poor efficiency (€0.13 /kWh); requires ~50 units, causing high landscape intrusion.

-----------------------------------------------------------------------
Recommendation:
-----------------------------------------------------------------------
The Enercon E33 offers the best balance of economic viability, ecological compatibility, and technical reliability.
Environmental Considérations.
• Located within a natural regional park → high environmental sensitivity.
• Enercon E33 minimizes visual, acoustic, and ecological impact compared to other models.
• Centralized installation reduces land disturbance and infrastructure footprint.
• Storm resilience analysis confirms optimal performance under typical wind conditions.

-----------------------------------------------------------------------
File Contents:
-----------------------------------------------------------------------
• Wind Turbine Analysis.ipynb – Main Jupyter Notebook with analysis, calculations, and visualizations.
• csv_Ouessant_48.455102_-5.097626_fixed_23_180_PT30M.csv - Wind speed at Ouessant at 10m and 100m
• Wind Turbine Ouessant.ppt - Presentation of the results and findings

-----------------------------------------------------------------------
Requirements:
-----------------------------------------------------------------------

Python 3.9+
Recommended environment: Jupyter Notebook / JupyterLab
Python Libraries: pandas, numpy, matplotlib, seaborn, scipy

-----------------------------------------------------------------------
Dependencies
-----------------------------------------------------------------------
Install dependencies using:
pip install pandas numpy matplotlib seaborn scipy

-----------------------------------------------------------------------
How to Run:
-----------------------------------------------------------------------
1. Clone the repository:
Wind-Turbine-Assessment.git
csv_Ouessant_48.455102_-5.097626_fixed_23_180_PT30M.csv
 
2. Open the notebook:
jupyter notebook "Wind Turbine Analysis.ipynb"

3. Run all cells sequentially to reproduce the analysis, tables, and plots.
Results Summary

-----------------------------------------------------------------------
Outputs:
-----------------------------------------------------------------------

• Recommended turbine: Enercon E33
• Cost per kWh: €0.0371
• Capital cost: €2.6 M
• Environmental rating: Low visual and acoustic impact

-----------------------------------------------------------------------
Interpretation
-----------------------------------------------------------------------

This analysis supports France’s renewable energy objectives while ensuring ecological protection of the Isle of Ouessant.

-----------------------------------------------------------------------
Author & Notes
-----------------------------------------------------------------------
Prepared by: Lara Normand

This project is Part of the Centralesupelec and ESSEC Business School AIDAMS Bachelor.
The notebook uses Python-based reproducible methods for statistical inference.
