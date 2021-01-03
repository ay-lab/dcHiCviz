# dcHiC Visualization

Visualization for dcHiC files in Regeneron manuscript. To view the full application, please visit [https://github.com/ay-lab/dcHiC](https://github.com/ay-lab/dcHiC). 

The following examples were created using dcHiC's standalone visualization utility, which allows for single-command creation of beautiful, standalone HTML files that allow for interactive compartment/genomic visualization. Each file has a set of controls on the top, which allow users to search by region or by gene. These files, available for download in the GitHub and created using IGV Javascript, will take a few seconds to load. 

### dcHiC-HOMER comparison 

See [this page](https://jeffreyywangg.github.io/dcHiCviz/dchic_homer.html) for a comparison of HOMER and dcHiC compartments, demonstrating a strong similarity in A/B compartment calls between MFA and PCA-based methods. It contains the following tracks: 
```markdown
dcHiC Compartments
HOMER Compartments
mESC/NPC LaminB1 Profile
```

### Complete Mice Neural Differentiation Comparison (with dcHiC)

See [this page](https://jeffreyywangg.github.io/dcHiCviz/multiWayMiceComplete.html) for complete mice neural differentiation overview. It contains the following tracks: 
```markdown
dcHiC Compartments
mESC/NPC LaminB1 Profile
RNA-Seq Data
ChIP Signals - H3K9me3, H3K4me3, H3K4me1, H3K27ac
```

Using the search feature, it is easy to explore the following genes:  
Notable **mESC**-specific genes include: Dppa2/4, Zpf42   
Notable **NPC/CN**-specific genes include: Ptn, Ephb1, Dcx, Rmst, Top1 (significant A-compartment change) 
Notable **control** genes include: Pou5f1, Actb

### Hematopoiesis Visualization

See [this page](https://jeffreyywangg.github.io/dcHiCviz/hematopoiesis.html) for compartment dynamics during mice hematopoetic differentiation. This file also contains TPM values for 8 of the cell lines. 

Two notable genes with significant decreasing A-compartment changes include **Myc/Pvt1** and **Meis1**. Others include **Runx2, Sox6, and Abca13**. 

### Cancerous vs. Normal Breast Tissue 

To view cancerous vs normal PC compartments for breat tissue, see [this page](https://jeffreyywangg.github.io/dcHiCviz/breast_cancer_vs_normal.html). A few notable genes to explore include **HS3ST2, TRPC6, MIR1246**. 
