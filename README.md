
Matplotlib - The Power of Plots

Background
This respository apply a Python Matplotlib to visualize a real-world pharmaceutical data. The data is sourced from Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

These analysis used a complete data from their most recent animal study in two datasets in CSV format. Data set one is Mouse_metadata.csv wich includes 249 mice identified data with SCC tumor growth were treated through a variety of drug regimens, and their Sex, Age_months and Weight (g) identified. The other dataset is Study_results.csv file which includes the results of the study in each columns Mouse I,Timepoint,Tumor Volume (mm3), and Metastatic Sites.

The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The analysis also generated all of the table and figures needed for the technical, and top-level summary report of the study. For this analysis both datasets imported, merged,cleaned and the aggregate data diplayed in to Python Pandas dataframes, visualized in Matplotlib, and other libraries used in order to make a stastical analysis. The project is conducted in Jupyter notebook to showcase, and communicate the analysis report the following link is created: Jupyter Notebook Viewer

Observable Trends
The bar graph showed the Drug Regimen Capomulin has the maximum mice number (230), and Zoniferol has the smaller mice number (182).By removing duplicates the total number of mice is 248. The total count of mice by gender also showed that 124 female mice and 125 male mice.


The correlation between mouse weight, and average tumor volume is 0.84. It is a strong positive correlation, when the mouse weight increases the average tumor volume also increases.


The regression analysis helped us to understand how much the average tumor volume (dependent variable) will change when weight of mice change(independent variables). The R-squared value is 0.70, which means 70% the model fit the data, wich is fairely good to predict the data from the model. Higher R-squared values represent smaller differences between the observed data, and the fitted value. 70% the model explains all of the variation in the response variable around its mean.


From the selected treatments Capomulin and Ramicane reduces the size of tumors better.
