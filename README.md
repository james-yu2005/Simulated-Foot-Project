Tensile Testing of Simulated Foot and Material Properties Analysis
Overview
This project involves the simulation and testing of a foot part in the PASCO Lab Tensile Testing setup. The goal was to analyze the material properties of the simulated foot through data analysis and improve its design using SolidWorks. The analysis was done using a combination of Python (NumPy, Matplotlib, Linear Regression) and Minitab (statistical tools, graphing, and linear regression) to extract the material properties, which were then verified and used to modify the part for better performance in tensile testing.

Steps Taken
1. Simulated Foot in PASCO Lab Tensile Testing
A foot part was simulated and subjected to tensile testing using the PASCO Lab.
Data collected from the tests included displacement, force, and time.
2. Data Analysis Using Python
The collected data was analyzed using a Python notebook with the following tools:
NumPy: For data manipulation and mathematical calculations.
Matplotlib: For plotting graphs to visualize the force-displacement relationship.
Linear Regression: To find the linear region of the stress-strain curve and calculate material properties.
3. Data Analysis Using Minitab
Minitab was used to analyze the data further using its powerful statistical tools:
Subset Data: Used to focus on specific regions of the data (e.g., linear stress-strain region).
Statistical Graphing: Graphs like histograms and box plots were used to analyze the distribution of material properties.
Descriptive Statistics: Calculated mean, standard deviation, and other metrics for key variables (e.g., force, displacement).
Calculator Functionality: Used to compute new columns (e.g., stress/strain ratio).
Linear Regression: Performed to fit a model to the stress-strain curve and extract material properties like Young’s Modulus and yield strength.
4. Verification Using SolidWorks
The material properties obtained from both Python and Minitab were used in SolidWorks for further simulation.
SolidWorks analysis helped verify that the material properties were valid and similar to expected values.
5. Modification of Simulated Foot Part
Based on the findings, the simulated foot part was modified in SolidWorks:
Increased Moment of Inertia (MOI).
Incorporated an I-beam structure to enhance the part's resistance against tensile forces.
6. 3D Printing and Final Testing
The modified foot part was 3D printed.
The new part was tested in the PASCO Lab Tensile Testing setup.
The modified design showed better performance under tensile testing, confirming that the design changes led to improved material resistance.
Technologies Used
Python: NumPy, Matplotlib, Linear Regression.
Minitab: Data Subsetting, Statistical Graphing, Descriptive Statistics, Linear Regression.
SolidWorks: Material Property Analysis, 3D Modeling, and Simulation.
PASCO Lab: Tensile Testing Equipment.
Conclusion
The combination of simulated testing, data analysis using Python and Minitab, and solid design verification in SolidWorks led to a significant improvement in the material's performance under tensile testing. The modified foot part exhibited better resistance, validating the design changes.

Future Improvements
Further refine the material properties analysis by exploring more advanced regression models.
Experiment with different design modifications to optimize the foot part further.
