# Brief Description of Supplementary Tables

**Supplementary Table S1:** Quality assessment and exclusion strategy for the 1112 subjects originally in the ABIDEI
project. First, the subjects with missing anatomical or functional files were excluded. Second, all subjects from the
imaging site Stanford were excluded as it is the only site with spiral image acquisition protocol. Third, all subjects
from the imaging site Leuven-1 were excluded due to unknown repetition times for the functional scans. Fourth, to
assess the quality of the raw images in ABIDE-I, we have used the information on raters’ decisions available from the
Preprocessed Connectome Project (PCP), and the subjects whose raw image quality was described as ‘fail’ by both
the raters were excluded. The raw images of the subjects that survived these exclusions were preprocessed. After
preprocessing the raw fMRI data, we applied the following criteria to exclude participants from the analysis. Subjects
were excluded if the FC distribution deviated significantly from normal distribution, or if the FC distribution showed
a noticeable distance dependence. We additionally excluded subjects that showed a noticeable correlation between
quality control (QC) variables and FC values, or if the QC-FC correlations showed a noticeable distance dependence.
After removing subjects based on these exclusion criteria, we were left with 395 subjects in the ASD group and 425
subjects in the HC group. The subjects that are included in our study are indicated and for the subjects that are
excluded, the reason for exclusion is marked in the respective columns.

**Supplementary Table S2:** The values of the group-wise average of the network measures namely average FRC of
edges, average ORC of edges, average clustering coefficient, modularity, average shortest path length, average node
betweenness centrality, global efficiency and average local efficiency, on the FCNs for the two groups (ASD versus
HC). We evaluated the differences between the two groups across the 49 graph densities in the range 0.02 − 0.5 of
FCNs considered in this study by using a two-tailed two-sample t-test, and further used a false discovery rate (FDR)
correction to correct for multiple comparisons and control the occurrence of false positives (see Methods). This table is
organized into three columns for every network measure with the first two columns containing the group wise average
and their standard error value for ASD and HC at every graph density threshold. The third column denotes the FDR
corrected p-values and the color of each cell in this column signifies the presence of significant differences between the
two groups (FDR corrected p < 0.05). Visualization of this data is provided in Figure 2 and Supplementary Figure
S1.

**Supplementary Table S3:** The terms associated with behavior, cognition and perception obtained from Neurosynth
tool for the set of brain regions belonging to the seven RSNs with significant between-group differences in 
node FRC and clustering coefficient. The frequency of occurrence of the terms associated with an RSN were
tested for statistical significance by comparing with the frequencies obtained from random surrogate brain regions
and further subjected to FDR correction with alpha equal to 0.05 (see Methods). The terms that survived the FDR
correction are presented in this table along with their frequencies. The terms and their frequencies in this table are
visualized as word clouds in Figure 4.

**Supplementary Table S4:** Brain regions that show significant between-group differences (ASD versus HC) based
on the network measures node FRC, node ORC, clustering coefficient and node betweenness centrality. To evaluate
the between-group differences in each of the 200 brain regions, we first computed the area under the curve (AUC)
for a given network measure across the 49 graph densities considered in this study and their group-wise average was
compared using two-tail two-sample t-test and corrected for multiple comparisons using FDR with alpha set to 0.05.
Note that these regions of interest in the brain were defined by the Schaefer atlas that parcellates the brain into
200 regions that belong to one of the seven RSNs. All brain regions have a common prefix ”7networks “ which has
been removed for convenience. A cell contains the value ‘none’ if a network measure has not identified a brain region
belonging to the RSN.

**Supplementary Table S5:** Data relating to author, year, DOI, number of participants, mean age, intellectual
abilities, target area, stimulation methodology and parameters, cognitive / behavioral measures and outcomes and
adverse reactions for both experimental and control group (if applicable) extracted from previous published studies
that have passed our eligibility criteria for relevance (see Methods) and used TMS or rTMS in ASD patients and have
reported positive outcomes post stimulation.

**Supplementary Table S6:** Data relating to author, year, DOI, number of participants, mean age, intellectual
abilities, target area, stimulation methodology and parameters, cognitive / behavioral measures and outcomes and
adverse reactions for both experimental and control group (if applicable) extracted from previous published studies
that have passed our eligibility criteria for relevance (see Methods) and used tDCS in ASD patients and have reported
positive outcomes post stimulation.

**Supplementary Table S7:** Mapping between the 200 brain regions defined by the Schaefer atlas and the corresponding
Brodmann areas. A Schaefer ROI was mapped to a Brodmann area if the MNI centroid coordinate of the
Schaefer ROI lies within the Brodmann area. The mapping was performed using the tool MRIcron. We identify the
brain regions whose stimulation with non-invasive brain stimulation methods (TMS / tDCS) of ASD patients resulted
in positive behavioural and cognitive outcomes from previous published studies (see Methods). The set of Schaefer
ROIs that were mapped to these target regions are indicated along with the node-level network measures that identify
the Schaefer ROIs to show significant between group differences.
