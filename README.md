# Tablesofnumbers
Analyze tables of numbers

#Download at: 
https://github.com/adhroso/Tablesofnumbers.git
or 
git clone git@github.com:adhroso/Tablesofnumbers.git

Data is visualized at: http://users.wpi.edu/~adhroso/table_analysis.html
Analysis results can also be downloaded from: http://users.wpi.edu/~adhroso/cell_benign_relation.png and http://users.wpi.edu/~adhroso/cell_malignant_relation.png

Data analytics is the process that examines raw data to uncover relations, novel patterns and information to help experts better interpret the results. With the technology advancements we are now generating more data than ever before, thus it is important to develop new visual aids to help the process of analytics.

In this work we attempt to discover relations between the size of cancerous cells versus non-cancerous cells. Our dataset comes from the University of Irvine, California (Breast Cancer Wisconsin Data set. Dataset is composed of 10 different attributes: clump thickness, uniformity of cell size, uniformity of cell shape, marginal adhesion, single epithelial cell size, bare nuclei, bland chromatic, normal nucleoli, mitoses and class (whether it comes from cancerous or non cancerous cell). Finding correlations between these attributes provides significant insights in which will allow researchers to focus and further study those attributes in order to identify the regulatory mechanisms responsible.

In order to visualize this dataset you must first download the dataset and all source code file(s) at https://github.com/adhroso/Tablesofnumbers.git. In addition, you must place these files in the web directory of your web server.

To visualize this dataset we employed parallel coordinates. One of the advantages of using Parallel coordinates is the ability to visualize large dimension datasets all at once. Thus, it allows us to uncover unknown correlations.


After a careful analysis of different attributes, we found that there are no clear correlations between the size of cell between cancerous and non cancerous patients. This includes other attributes as well. It is easy to see from cell_malignant_relation.png and cell_benign_relation.png (see links above), cancerous and non cancerous patients have significant overlap with respect to cell size.
 
