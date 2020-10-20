# GROUP-9-PROJECT-1

**David Marobella**
Jupyter Notebook:
- Location_Analysis is my Jupyter Notebook code.

Source Data: 
- House_price_multifeatures is the raw data we used.
- FL Demos by age race gender county is the raw data from Demographic Estimating Conference
  Database.

CSV files:  
- clean.csv is the team data used that Tyler cleaned up.
- clean1.csv is my file of the clean file which adds in County.
- clean FL Demos.csv is the CSV file that was cleaned up file of FL Demos by age race gender county using Jupyter Notebook.
- merged_files is the merged files for the clean FL Demos and the clean1 files.

PNG figs: Created by Location_Analysis.ipynb
- Average Age by County PNG File is the scatter plot for Average age by top counties.
- Average Age vs Value of Home Scatter is the scatter plot for Average Age of County vs Value of Home.
- Distance to Coast Scatter is the scatter plot for the Value of Home vs the Distance to the Coast.

**Tyler Hunt**
Jupyter Notebook:
- Parcel_bc.ipynb summary - This file imports data from ‘clean.csv’ for those that have FL vacation homes but whose primary residence is in NC, SC or VA. This Jupiter notebook dives into how the square footage of a home is related to the value of the home as well as how square footage is distributed amongst the owners in the dataset. Furthermore, this notebook was used to identify and visualize where such owners tended to live and FL and where the most expensive homes could be found.

PNG figs: Created by parcel_bc.ipynb
- ‘SquareFootageHistogram.png’ - Shows distribution of square footage for vacation homes in FL for owners who primarily reside in NC, SC and VA
- ‘SquareFootageScatter.png’ - Shows correlation between square footage and home value for vacation homes in FL for owners who primarily reside in NC, SC and VA
- ‘Heatmap_hv.png’ - Shows a heat map of where vacation homes are located. Weights are based on value of home. Example: A 6 million dollar home would have a larger point radius and intensity than a 30k dollar home.


**Ai-Jiuan Wu**
Jupyter Notebooks:
- house_data_raw2.ipynb - generate the clean2.csv file by adding Distance to Hydrant and CountyName data from House_price_multifeatures.csv  to clean.csv file.
-public_community.ipynb - performed the data analyses looking at the impacts of fire protection, property crime and education on home prices.  Prices for vacation and county-wide homes.

Source Data:
 - House_price_multifeatures.csv  - original data source from Kaggle. 
 - 'FLCounties_Ed_Crime.csv'- Compiled by pulling data from FL Department of Law Enforcement and Florida Department of Education.
- 'clean2.csv' - generated by house_data_raw2.ipynb code (see above).

PNG figs: Created by public_community.ipynb.  Scatter plots and correlation plots were not printed but are in jupyter notebook.
- 'VacHomes_county.png': Country distributions for all NC, SC, and VA-resident vacation homes in FL.
- 'VacHomes_PPC.png': PPC rating distributions for all NC, SC, and VA-resident vacation homes in FL.
- 'AvgHomeValue.png': Comparison of avg home value for NC, SC, and VA-resident vacation homes vs. all homes in a particular county.
- 'AvgPPC.png':Comparison of avg PPC ratings  for NC, SC, and VA-resident vacation homes vs. all homes in a particular county.
- 'PropertyCrimeRate.png': Proper Crime Rate for each county where NC, SC, and VA-resident vacation homes are. 
- 'crime.png': Property Crime Rate for each county in FL.
- 'ed.png': % Total Ed points for each county in FL.
- 'value.png': Home Values for each county in FL.

## Analysis of Home Type and Age of Home
### Coded by Autumn Demonet
Jupyter Notebook:
- house_attributes.ipynb is the code used to analyze the impact of home type and home age on the value of a property

PNG Files:
- fl homes by age lr.png is the scatter plot that compares Age of Home to its Value with the linear regression annotated
- florida house type pie chart.png is the pie chart of House Types that are owned by Florida residents
- home type boxplot drop.png is the boxplot of Home Values grouped by Home Type with outliers dropped
- home type boxplot.png is the original box plot of Home Values grouped by Home Type used to establish outliers
- house by build year.png shows the most popular build years for homes in the data set
- house type pie chart.png is the pie chart of House Types that are owned by NC, SC, and VA residents
- houses by build type.png is a bar chart representing the five different build types
- nc homes by type.png is a pie chart of home types owned by NC residents
- sc homes by type.png is a pie chart of home types owned by SC residents
- va homes by type.png is a pie chart of home types owned by VA residents
- value cs second homes by age.png is a scatter plot of Stacked Condo homes that compares Age of Home to its Value with the linear regression annotated
- value second home by age.png is a scatter plot of second homes that compares Age of Home to its Value with the linear regression annotated
- value sf second home by age.png is a scatter plot of Single Family second homes that compares Age of Home to its Value with the linear regression annotated

**Joseph Pegram**

Jupyter Notebook:
nat_disasters.iipynb

Images:
Scatter Plot Visual: Value of Home based on the Distance to Sinkhole
Box plot Visual: Sinkhole Comparison based on State (NC, SC, VA)
Bar Chart Visual: The count of Location Windspeed based on state (NC, SC, VA)
Pie Chart Visual: Terrain Comparison by State (NC, SC, VA)
Pie Chart Visual: Windborne Debris Comparison by State(NC, SC, VA)
Box Plot Visual: Value of Home based on the Terrain

**Mikael Hall**

Jupyter Notebook: 
- Home_Amenities.ipynb
- House_Att.ipynb

Source Data:

clean4.csv
PNG images: 
- NumberofStories boxplot
- NumberofStories2 boxplot
