12/02/2019

Text font explaination
1 - Bold texts: need to modify or rewrite later

Wet Lab Methods
1. Flow cytometry methods are tedious. Is it essential to show the methods? Should I describe it in details?
Put the place holder in the manuscript for Goncalo.
2. Need to know more about the sampling methods from Goncalo.
3. Need to make spreadsheets for barcodes being used in supplementary.
4. Will describe the details of RTPR library preparation in the methods. Should I do the same for 16S library preparation? Or point to somewhere else.
Do not need to have too many words.


Dry Lab Methods
1 -  beta group significance
1.1 Current way - Using aitchison distance matrix calculated from clr; beta-group-significance command in QIIME2. No replicates. Day as covariate. Depths 
are collapsed
1.2 Alternatives - Using DivNet to calculate beta diversity (Atchison and Bray-curtis) of ecosystems, but not sure how to calculate beta-group-significance. 
Not like alpha diversity, DivNet does not provde command for beta group significancae. There is also no errors for each beta diversity value. 
Have to confirm that if Euclidean in DivNet is Aitchison Distance

2 - PCA of samples and loadings
2.1 Decide to use rho > 0.85 at each depth and effect size > 1 for bacterioplankton as signficant OTUs
Decide to use rho > 0.65 at each depth and effect size > 1 for virioplankton as signficant OTUs
Look for how they decide the cutoff of effect size 
Look for other papers in microbes in marine ecosystems
2.2 Found that most of ASVs or OTUs have effect size > 1 so decided to use all of ASVs and OTUs to make sample PCA and loadings PCA
2.3 Can OTU loadings figures show different OTUs contribute to sample diversity? Points or vectors?
2.4 Need to fix the grouping color problems in PCA plots using Tianyi scripts

5 - Proportionality
5.1 - Do proportionality test between the two fractions.
5.2 - within each fraction, phylogenetically similar features have approximately equal ratio across days. Phylogenetically dissimilar features do not. but have 
strong asscociation in other ways


Discussion
1 - Move the advantages and disadvantages of marker gene approaches compared to metagenome approaches to Discussion or Conclussion
2 - How can I determine that the environmental features influence bacterioplankton community first and then virioplankton community change according to the
 change of bacterioplankton community change

Plans
1. Do analysis in traditional ways and compare with CoDa analysis
2. Solidify anticyclonic vortex statement using oceanographic data from Azores. Group meeting
3. RTPR comparisons from both fractions in Dicussion and Supplementary?
