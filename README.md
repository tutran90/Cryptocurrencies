# **Cryptocurrencies**

## **Overview**

The purpose of this project was to use unsupervised machine learning modules to find patterns in cryptocurrencies currently being traded. 

The data used for this project is located in "crypto_data.csv". 

The following libraries and modules were used to conduct this unsurpervised machine learning project: 
* Pandas 
* HVPlot library 
* Plotly 
* Scikit Learn: StandardScaler, MinMaxScaler, PCA, and KMeans 

## **Results** 
The following data has no clear outcome. The goal is to find patterns with the current tradable cryptocurrencies. 

An elbow curve was use to find the best number of clusters to group the data, which was 4: 
![img](https://github.com/tutran90/Cryptocurrencies/blob/main/Elbow_curve.png). 

KMeans algorithm was then use to fit and transform the data. 

After scaling the data down to a more equal range it was plotted with both a 2D and 3D HVplot. 

A 3D scatter plot was created off of the PCA values; which is used to help speed up the machine learning algorithm. The clusters are grouped nicely, however if presenting it to shareholders, it may be confusing since we don't know exactly which cryptocurrency belongs to which class. A dataframe was created that was able to match the "Class" with each type of cryptocurrency. The dataframe could be modified to group all the cryptocurrencies by class, which would make it easier to read for the stakeholder. ![img](https://github.com/tutran90/Cryptocurrencies/blob/main/3d_scatter_plot.png)

The 2D scatter plot was very congested and did not show clear clusters of the processed data. The data had overlapped, therefore not able to give us a good picture of what the pattern was. A 3D scatter plot of the overall processed data could have given us a better picture of what the trend/pattern was. 
![img](https://github.com/tutran90/Cryptocurrencies/blob/main/2D_scatter_plot.png)

Overall, there is still room for improvement to show a concise pattern(s) between all the current trading cryptocurrencies but it is definitely a starting point to build off of. 