# Functional connectivity networks of ABIDE-I

## Background

In our study, to evaluate the utility of two discrete Ricci curvatures, Forman-Ricci curvature and Ollivier-Ricci curvature that have been recently ported to the domain of complex networks, as indicators of abnormal topological organization in resting state functional connectivity (FC) networks corresponding to individuals with **_autism spectrum disorder (ASD)_**. 

For this investigation, we analysed spatially and temporally preprocessed rs-fMRI images of 395 subjects with autism spectrum disorder (ASD) and 425 healthy controls (HC), using the CONN toolbox. Subsequently, 200 regions of interest (ROIs) or nodes were defined in the brain using the Schafer atlas, and a 200 × 200 functional connectivity matrix was generated for each subject by computing the Pearson correlation coefficient between the time-series of all pairs of nodes. The schematic overview of our preprocessing pipeline can be found below.

![schema image](https://github.com/asamallab/RicciCurvature-fMRInetworks/blob/main/fMRInetworks/ABIDE-I/README-SchemaImage.png)

**Functional Connectivity Matrices (FCM)**

The 200 × 200 functional connectivity matrices of every subject, that was obtained at the end of the preprocessing pipeline is available in the edgelist format (assuming the functional connectivity matrices as the adjacency matrices of complete graphs) in FCM directory.
The files contain three columns - source, target and correlation coefficient as edge attribute.

**Functional Connectivity Networks (FCN)**

From the functional connectivity matrices we extracted the maximal spanning tree of every subject using Kruskal's algorithm. By combining

* maximum spanning tree (MST) and 
* sparsity-based thresholding, 

we constructed functional connectivity networks (FCNs) over a wide range of graph densities between 0.02 or 2% edges and 0.5 or 50% edges, with an increment of 0.01 or 1% edges. 

The functional connectivity networks used in our study, is available in the edgelist format in FCN directory and is further organised by threshold value.The files in FCN contain three columns - source, target and correlation coefficient as edge attribute.

## CITATION
If you use the data from our repository for your work, please cite,
				ADD CITATION
