# TNT scripts for phylogenomics
In this repository are included the scripts published in the paper *An outline for phylogenomic analyses using TNT* by Ambrosio Torres, Pablo A. Goloboff and Santiago A. Catalano (Cladistics. 2020).
The scripts are completely described in the study mentioned above and most of them can be executed using the TNT Windows-menu version (Fig. 1) and using the command-line versions of TNT for Linux, Mac and Windows. The entire information about the scripts is also within the files themselves. This information is also available by typing in TNT (please make sure the script-files are in the folder where you are working):

    run NameOfTheScript.run help;

<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Figures/Fig1.png" alt="alt text" width="700" height="294">
</p>

**Figure 1.** Opening input files in the TNT Windows-menu version.
<br/>
<br/>

We provide sample datasets in the link below that may be used for testing the scripts presented here. However, we encourage you to use your own datasets in order to expand the number of datasets that have been used to test these scripts. In this way, with your help we will more easily notice the bugs and errors the scripts may be producing:
https://drive.google.com/file/d/1lTyVPjFP0HSw_-Kn13nfpXb3lakHx3WS/view?usp=sharing

## List of scripts
<ol>
<li>CompileGenes.run</li>
<li>GeneOccupancy.run</li>
<li>PhylogenomicSearch.run</li>
<li>PhylogenomicSupport.run</li>
<li>SearchGeneTrees.run</li>
<li>GeneSupFrequency.run</li>
<li>TreeDistMatrix.run</li>
</ol>
<br/>
<br/>

### 1. CompileGenes.run
This script enables the user to concatenate any number of data files into a single matrix in TNT format. When the script is run from TNT Windows-menu version, a dialog box is opened to define the settings (Fig. 2). In Linux, Mac and Windows command-line versions of TNT, the script should be run with arguments (see the help of the script).
<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Figures/Fig2.png" alt="alt text" width="600" height="322">
</p>

**Figure 2.** Dialog box for *CompileGenes.run*.
<br/>

### 2. GeneOccupancy.run
This script generates submatrices with sampling of taxa/genes that present a level of occupancy defined by the user. Two different conditions can be determined: (i) percentage of species a gene must present for to be sampled, (ii) percentage of genes a species must present for to be sampled. The script produces a submatrix in TNT format and a SVG file with information about taxon/gene occupancy (Fig. 3). This script should be executed using arguments in Linux, Mac and Windows command TNT versions (for more information see the help of the script).
<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Figures/Fig3.png" alt="alt text" width="600" height="332">
</p>

**Figure 3.** Example of graphical output from *GeneOccupancy.run*.
<br/>

### 3. PhylogenomicSearch.run
This script performs phylogenetic inference for phylogenomic datasets. The script enables the users to define multiple settings in a very simple way (e.g. the treatment of the gaps in the alignments, the use of different implied weighting schemes, the format of the output files, etc.) When the script is run from TNT Windows-menu version, a dialog box is opened to define the settings (Fig. 4).
<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Figures/Fig4.png" alt="alt text" width="600" height="332">
</p>

**Figure 4.** Dialog box for *PhylogenomicSearch.run*.
<br/>

### 4. PhylogenomicSupport.run
The script performs six different types of support analyses. In addition the users have access to a comprehensive combination of possible settings. When the script is run from TNT Windows-menu version, a dialog box is opened to define the settings (Fig. 5).
<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Figures/Fig5.png" alt="alt text" width="580" height="332">
</p>

**Figure 5.** Dialog box for *PhylogenomicSupport.run*.
<br/>

### 5. SearchGeneTrees.run
The script calculates the gene trees from a TNT dataset where each gene is included as a different block/partition (e.g. output files from *CompileGenes.run*). When the script is run from TNT Windows-menu version, a dialog box is opened to define the settings (Fig. 6). In Linux, Mac and Windows command-line versions of TNT, the script should be run with arguments (see the help of the script).
<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Figures/Fig6.png" alt="alt text" width="500" height="322">
</p>

**Figure 6.** Dialog box for *SearchGeneTrees.run*.
<br/>

### 6. GeneSupFrequency.run
This script calculates the percentage of individual gene trees supporting the nodes of a reference tree (e.g. concatenation-based tree). Some authors referred to this measure as Gene Support Frequency (GSF; Gadagkar et al. 2005 doi: 10.1002/jez.b.21026&59; Salichos et al., 2014 doi: 10.1093/molbev/msu061). This script presents the GSF values in three different ways (Fig. 7).
<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Figures/Fig7.png" alt="alt text" width="600" height="522">
</p>

**Figure 7.** Example of graphical outputs from *GeneSupFrequency.run*. (a) Heatmap of the GSF for the Species tree (concatenation-based tree). Nodes supported by the gene tree (green box); nodes supported by the gene tree, but with some of the descendants missing in the gene tree (yellow box); nodes not supported by the gene tree (red box). The information is also presented as stacked bar plots (Nd= node number; Bl= block/gene tree; Supp= supported). (b) Species tree with values of Gene-support frequency. Labels above branches = node number (Nd). Labels below branches =   frequency of gene trees in agreement with reference tree (Yellow + green in heatmap ) | frequency of gene trees that present the node (Green in heatmap; Gene-support frequency).(c) Description of the definitions and color code of clades showing full matching, agreement with and in contradiction to the reference tree.
<br/>

### 7. TreeDistMatrix.run
This script calculates a distance matrix for a set of trees. The users could choose among four different metrics (SPR moves, SPR difference, normalized Robinson-Foulds and the distortion coefficient). Two outputs are produced: the distance matrix in CSV format and a heat map in SVG format (Fig. 8).
<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Figures/Fig8.png" alt="alt text" width="404" height="380">
</p>

**Figure 8.** Example of graphical output from *TreeDistMatrix.run*.

