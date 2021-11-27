# Functional connectivity networks of ABIDE-I

## Background

In our study, to evaluate the utility of two discrete Ricci curvatures, Forman-Ricci curvature and Ollivier-Ricci curvature that have been recently ported to the domain of complex networks, as indicators of abnormal topological organization in resting state functional connectivity (FC) networks corresponding to individuals with **_autism spectrum disorder (ASD)_**. 

For this investigation, we analysed spatially and temporally preprocessed rs-fMRI images of 395 subjects with autism spectrum disorder (ASD) and 425 healthy controls (HC), using the CONN toolbox. Subsequently, 200 regions of interest (ROIs) or nodes were defined in the brain using the Schafer atlas, and a 200 × 200 functional connectivity matrix was generated for each subject by computing the Pearson correlation coefficient between the time-series of all pairs of nodes. The schematic overview of our preprocessing pipeline can be found below.



![schema image](https://github.com/asamallab/RicciCurvature-fMRInetworks/blob/main/fMRInetworks/ABIDE-I/README-SchemaImage.png)

## Functional Connectivity Matrices (FCM)

The 200 × 200 functional connectivity matrices of every subject, that was obtained at the end of the preprocessing pipeline is available in the edgelist format (assuming the functional connectivity matrices as the adjacency matrices of complete graphs) in [FCM](https://github.com/asamallab/RicciCurvature-fMRInetworks/tree/main/fMRInetworks/ABIDE-I/FCM) directory.
The files contain three columns - **source**, **target** and **correlation coefficient** as edge attribute. (Please note that our networks are undirected)

## Functional Connectivity Networks (FCNs)

From the functional connectivity matrices we extracted the maximal spanning tree of every subject using Kruskal's algorithm. By combining

* maximum spanning tree (MST) and 
* sparsity-based thresholding, 

we constructed FCNs over a wide range of graph densities between 0.02 or 2% edges and 0.5 or 50% edges, with an increment of 0.01 or 1% edges. 

The FCNs used in our study are available in the edgelist format in [FCN](https://github.com/asamallab/RicciCurvature-fMRInetworks/tree/main/fMRInetworks/ABIDE-I/FCN) directory, and are further organised by threshold value.
The files in FCN contain three columns - **source**, **target** and **correlation coefficient** as edge attribute. (Please note that our networks are undirected)

## Supporting files

1. **_demographic_table.tsv_**

Table containing the demographic information such as imaging site, unique subject identifer, age, gender and cohort (healthy/ASD) of all the 820 subjects included in our study.

2. **_Schaefer200.txt_**

A list of all the 200 regions of interest (nodes) in the Functional connectivity networks. Please note that these regions are encoded as integers from 0 to 199 (in order) in the functional connectivity networks provided.

## Supplementary Tables

An Excel workbook containing all the Supplementary Tables S1-S7 for our paper can be downloaded [supplementary_tables](https://github.com/asamallab/RicciCurvature-fMRInetworks/tree/main/fMRInetworks/ABIDE-I/supplementary_tables) directory. A brief description of each Supplementary Table is provided as a README file inside the directory.

## CITATION
If you use the data from our repository for your work, please cite,
				
				ADD CITATION
