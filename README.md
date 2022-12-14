# kmeans

# TABLE OF CONTENTS #

[System Objectives and Description](#System-Objectives-and-Description)

[System Requirements and Installation](#System-Requirements-and-Installation)

[Application components](#Application-components)

[Sample output](#Sample-output)

[References](#References)

[Contributors](#Contributors)

[License and Copyright](#License-and-Copyright)

# System Objectives and Description
		
kmeans is a program aimed at implementing the k-means clustering algorithm on predefined datasets. 

To assist in the implementation of the k-means algorithm, functions were written to achieve the following:
- finding the Euclidean distance between two data points
- reading csv files 
- find the nearest centroid to each data point of all the centroid 
- visualizing the clusters

The program should output the following:
1. The number of countries belonging to each cluster
2. The list of countries belonging to each cluster
3. The mean Life Expectancy and Birth Rate for each cluster

# System Requirements and Installation 

As the program is coded in Python, in order to run and test the code, the following IDE is required:

__- The Python IDE:__
To download the Python IDE, click on the following link to access the official Python website: 
*https://www.python.org/downloads/*

Alternatively, you can download Visual Studio Code which also supports compatibility for Python code
- To download the Visual Studio Code IDE including the Coding Pack for Python, click on the following link: 
*https://code.visualstudio.com/docs/python/coding-pack-python*

In order to perform machine learning algorithms, you will also be required to install the Python SciPy, 
NumPy, Matplotlib and Sci-Kit learn packages. 

To install these packages, do the following:

- Open the command prompt or terminal on your device
- To install SciPy, type “__pip install scipy__” and press Enter.
- To install NumPy, type “__pip install numpy__” and press Enter.
- To install Matplotlib, type “__pip install matplotlib__” and press Enter.
- To install Sci-Kit, type “__pip install sklearn__” and press Enter.

# Application components

To improve the structure and readability of the code, the __kmeans.py__
is comprised of the following code blocks:

- __K-means algorithm pseudocode__: this code block provides a bried, but concise 
  pseudocode of how the k-means algorithm will be implemented.
- __References__: in this block, links are provided as acknowledgement of external resources used
  for this program.
- __Libraries__: in this block all external packages (csv, numpy and matplotlib) are imported. 
- __Functions__: in these code blocks all required functions are declared. 
The following functions were used:
1. __euclidean_dist_calc__ (this function computes the distance between two data points)
2. __read_csv__ (this function reads in data from csv files)
3. __nearest_centroid__ (this function finds the closest centroid to each point of all the centroids)
4. __cluster_scatterplot__ (this function helps to plot and visualize the clusters)

- __Initialization procedure___: the code blocks in the initialization procedure is used to 
  initialize the initial number of clusters and iterations. 
It is also used to get the following input from the user:
1. the name of the dataset they want to use.
2. their desired number of clusters. 
3. their desired max number of iterations. 

Random centroids is also initialized from the csv file and 
added to the 'centroids' list. 

__Implementation of the k-means algorithm__: 
in this code block you will:
1. iterate through the number of iterations, 
2. find the closest centroid to each data point and assign the target point to that centroid's cluster, 
3. calculate the new mean of all points in the cluster, 
4. visualize the cluster after each iteration,
5. and initialize the final cluster data

__Display results__: 
1. Print the number of countries belonging to each cluster;
2. Print the list of countries belonging to each cluster;
3. Print the mean life expectancy and birth rate for each cluster

# Sample output

![kmeans1](https://user-images.githubusercontent.com/102178512/182128718-56b929b5-f27b-465c-8367-0b221fb70e4c.jpg)

![kmeans2](https://user-images.githubusercontent.com/102178512/182128760-f9ee2e36-108a-4d0b-9eea-22c7740acf34.jpg)

![kmeans3](https://user-images.githubusercontent.com/102178512/182128826-584934dd-143b-4e3d-8dd7-2a5d7339d2a9.jpg)

![kmeans4](https://user-images.githubusercontent.com/102178512/182128889-dd094aa8-3630-48ba-b4ff-e757e00e7797.jpg)

![kmeans5](https://user-images.githubusercontent.com/102178512/182129489-738435ff-9f1b-4612-a704-737f5753a8f7.jpg)

![kmeans6](https://user-images.githubusercontent.com/102178512/182129527-d8a05667-6b3b-4315-96a1-0746083b6724.jpg)

![kmeans7](https://user-images.githubusercontent.com/102178512/182129560-c568486b-f835-43f8-8bfc-27e27c4c3681.jpg)

# References 

__Calculating Euclidean distance:__

*https://www.delftstack.com/howto/numpy/calculate-euclidean-distance/*

__Reading CSV files:__

*https://docs.python.org/2/library/csv.html/*

__Creating cluster scatterplots:_

*https://www.askpython.com/python/examples/plot-k-means-clusters-python*

# Contributors

Tammy-Lee Bastian, HyperionDev

tammyleebastian@gmail.com

# License and Copyright

  © Tammy-Lee Bastian
  
  Licensed under the [MIT License](LICENSE)
