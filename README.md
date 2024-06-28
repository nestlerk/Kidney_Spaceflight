# Kidney_Spaceflight
## This repo contains the code and related metadata files to generate figures 4, 5, 6a-b, and 8 for the manuscript: Cosmic kidney disease: an integrated pan-omic, physiological and morphological study into spaceflight-induced renal dysfunction.

## These analyses used files generated from three enrichment analysis: Disease term enrichment (DisGeNET), GO term (biological processes), and KEGG pathway enrichment analysis. See below for details.

### DisGeNET analysis
#### DisGeNET analysis was performed using Metascape (https://metascape.org/gp/index.html) with default settings. Differentially expressed gene lists (p.value <0.05) from each dataset were imported into Metascape. Mouse genes were imported as mouse and analyzed as human. DisGeNET outputs containing enriched human disease terms (-LogP >2) were downloaded and visualized using Python’s seaborn and matplotlib libraries. The circle size represents –LogP values and the circle color represents gene ratio. 

### KEGG pathway analysis
#### KEGG pathway analysis was performed using Metascape with default settings. Differentially expressed gene lists (p. value < 0.05) from each dataset were imported into Metascape. Mouse genes were imported as mouse and analyzed as human. KEGG outputs containing enriched KEGG pathways (-LogP >2) were downloaded and visualized using Python’s seaborn and matplotlib libraries. The circle size represents –LogP values and the circle color represents gene ratio.

### GO enrichment visualization
#### Enriched GO terms were obtained from clusterProfiler outputs. GO enrichments containing biological process ontologies were visualized using Python’s seaborn and matplotlib libraries. The circle size represents –LogP values and the circle color represents gene ratio.

----

### Additionally, categorical heatmaps were generated from differentially expressed gene lists from the various proteomic and transcriptomic datasets. See below for details.

### Categorical heatmap
#### Significant genes (p. value < 0.05) were obtained from each kidney proteomic and transcriptomic dataset and ranked according to the log2 fold change direction and the number of times observed across all datasets. The highest ranked upregulated and downregulated genes were plotted using CoMut. (Citation: Crowdis, J., He, M.X., Reardon, B. & Van Allen, E. M. CoMut: Visualizing integrated molecular information with comutation plots. Bioinformatics (2020). doi:10.1093/bioinformatics/btaa554)
