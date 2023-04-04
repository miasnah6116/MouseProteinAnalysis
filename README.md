# Protein Expression in Down Syndrome Mice

CSC 621 - Machine Learning
Han Saim Jeong
Dr. Ruth Cheng

## Project Description

This project utilizes a dataset consisting of the protein expression of 77 proteins in mice.
The mice used were either control or Ts65Dn mice (trisomic) to mimic Down Syndrome conditions.
Context fear conditioning and the drug Memantine were used as additional variables to manipulate.

According to these variables, the mice were separated into 8 different classes:
c-CS-s: control mice, stimulated to learn, injected with saline (9 mice)
c-CS-m: control mice, stimulated to learn, injected with memantine (10 mice)
c-SC-s: control mice, not stimulated to learn, injected with saline (9 mice)
c-SC-m: control mice, not stimulated to learn, injected with memantine (10 mice)
t-CS-s: trisomy mice, stimulated to learn, injected with saline (7 mice)
t-CS-m: trisomy mice, stimulated to learn, injected with memantine (9 mice)
t-SC-s: trisomy mice, not stimulated to learn, injected with saline (9 mice)
t-SC-m: trisomy mice, not stimulated to learn, injected with memantine (9 mice)

The aim of the project was to identify the subsets of proteins that were discriminant between the classes.

### How to Run the File

The file is a .ipynb file that can be run in any IDE that runs python. Ideally, Jupityr notebook would be utilized.

#### How to Use the File

By running the python code, the results and visualizations can all be seen.
The parallel coordinates graphs at the end are all interactable graphs and from these the results can be determined.
By selecting for specific clusters and classes, or combinations of the two thereof, specific patterns can be isolated
and proteins critical for the differences between classes can be identified.

The following link is an excellent tool for learning how to use and interact with the parallel coordinates plots
utilized in this project.
https://plotly.com/python/parallel-coordinates-plot/

##### Credits

I would like to thank UCI for their machine learning repository in which I found this data set.
https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression

I would also like to thank Dr. Ruth Cheng for teaching the machine learning course and for imparting
the knowledge used to implement this project.