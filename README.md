# IR2022_A2_47

## Assignment Info
Course: Information Retrieval [CSE508]  
Semester: Winter 2022  
Group: 47  
Assignment 2

## Repository Description
Q1.ipynb: complete code with comments and markdowns for question 1  
Q2.ipynb: complete code with comments and markdowns for question 2  
Report.pdf: report with all the observations, formulae and explanations for assignment  
Images: contains graphs and report images

## .gitignore Description
All the data files are stored in the Dataset folder which is present in the root folder.

## Dataset Description
Dataset chosen for this assignment is [Wikipedia Vote Network](https://snap.stanford.edu/data/wiki-Vote.html), a network of who-votes-on-whom. The network is a bidirectional graph of 7115 nodes and 103689 edges. Nodes in the network represent wikipedia users and a directed edge from node i to node j represents that user i voted on user j.

## Code Explanation

### Q1
- Methodology
  - Relevant libraries are imported
  - File is read
  - Adjacency Matrix, Adjacency List, Number of Nodes, Number of Edges, In-Degree List, Out-Degree List, Forward and Reverse Mapping of wikipedia users and nodes are created/determined
  - Average In-Degree is calculated
  - Average Out-Degree is calculated
  - Node with Max In-Degree is calculated
  - Node with Max Out-Degree is calculated
  - Density of Network is calculated
  - In-Degree Distribution is plotted
  - Out-Degree Distribution is plotted
  - Local Clustering Coefficient is calucalted for each node
  - Local Clustering Coefficient Distribution is plotted
- Explanation
  - Explanation of formulae, outputs and graphs can be found in the report


### Q2
- Methodology
  - Relevant libraries are imported (NetworkX is used for this question)
  - Directional Graph is made by reading the file
  - PageRank score is calculated for each node and top 10 nodes with highest PageRank score are displayed
  - Hubs score is calculated for each node and top 10 nodes with highest Hubs score are displayed
  - Authority score is calculated for each node and top 10 nodes with highest Authority score are displayed
- Explanation
  - Explanation and comparison of algorithms can be found in the report

## Report
![Report 1](/Images/Report/Report-1.png)  
![Report 2](/Images/Report/Report-2.png)  
![Report 3](/Images/Report/Report-3.png)  
![Report 4](/Images/Report/Report-4.png)  
![Report 5](/Images/Report/Report-5.png)
