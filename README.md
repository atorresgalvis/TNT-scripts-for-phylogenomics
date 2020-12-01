# TNT scripts for phylogenomics
In this repository are included the scripts published in the paper *An outline for phylogenomic analyses using TNT* by Ambrosio Torres, Pablo A. Goloboff and Santiago A. Catalano (Cladistics. 2020).
The scripts are completely described in the study mentioned above and can be executed using the TNT Windows menu version (Fig. 1) and using the command versions of TNT for Linux, Mac and Windows. The entire information about the scripts is also within the files themselves. In addition, this information could be accessed by typing in TNT (please make sure the script-files are in the folder where you are working):

    run NameOfTheScript.run help;

<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Fig1.png" alt="alt text" width="700" height="294">
</p>

**Figure 1.** Opening input files in the TNT Windows menu version.
<br/>
<br/>
## List of scripts
<ol>
<li>CompileGenes.run</li>
<li>GeneOccupancy.run</li>
<li>PhylogenomicSearches.run</li>
<li>PhylogenomicSupport.run</li>
<li>SearchGeneTrees.run</li>
<li>GeneSupFrequency.run</li>
<li>TreeDistMatrix.run</li>
<li>xxx.run</li>
</ol>
<br/>
<br/>
### 1. CompileGenes.run
This script allows the user to concatenate any number of data files into a single matrix in TNT format. When the script is run from TNT windows menu version, a dialog box is opened to define the settings (Fig. 2). In linux, mac and windows command TNT versions, the script should be run with arguments (see the help of the script).
<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Fig2.png" alt="alt text" width="600" height="342">
</p>
<br/>
**Figure 2.** Dialog box available when running *CompileGenes.run* from TNT windows menu version.

### 2. GeneOccupancy.run
Generates submatrices with sampling of taxa/genes that present a level of occupancy defined by the user. Two different conditions can be determined: (i) percentage of species a gene must present to be sampled, (ii) percentage of genes a species must present to be sampled.The script produces a submatrix in TNT format and a SVG file with information about taxon/gene occupancy (Fig. 3). This script should be executed using arguments in Linux, Mac and Windows command TNT versions (for more information see the help of the script).
<p align="center">
<img src="https://github.com/atorresgalvis/TNT-scripts-for-phylogenomics/blob/main/Fig3.png" alt="alt text" width="600" height="332">
</p>

**Figure 3.** Dialog box available when running *CompileGenes.run* from TNT windows menu version.
<br/>
### 3. PhylogenomicSearches.run
...
<br/>
### 4. PhylogenomicSupport.run
...
<br/>
### 5. SearchGeneTrees.run
...
<br/>
### 6. GeneSupFrequency.run
...
<br/>
### 7. TreeDistMatrix.run
...
<br/>
### 8. xxx.run
...


