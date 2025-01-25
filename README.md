DNA Methylation data analysis is the second session of the BioinfoHub at the Center for Molecular Medicine (CMM). The seminar is scheduled to take place on the 29th of January at the CMM lecture hall.

# Study design
In our group we have tested various constructs based on CRISPR-dCAS9 technology for epigenetic editing and the main aim of the shared dataset is to study on- and off target effects. Our guide (g)RNA, g8, is designed to target the BACH2 promoter, a transcription factor, implicated in various immune-mediated diseases. In the study design, we have further included a non-target control (NTC) gRNA with no homology to the human genome, as well as a construct with a “dead” catalytic domain.  

# Dataset
The shared files consists of:
1.	idat files (raw data)
2.	Meta-data (Excel)
3.	A mybeadcount function (.txt)

The data is derived from the Infinium MethylationEPIC array (Illumina), which measures DNA methylation levels of 850K sites genome-wide. 

# Learning objectives
In this workshop we will:
1.	Preprocess the data, including:
- QC
- Probe filter using the ChAMP package
- Normalization using the NOOB funcNorm function
- Exploratory analysis using density, MDS, hierarchical clustering and PCA
2.	Conduct differential methylation analysis using Limma
3.	Generate interactive Volcano plots to explore potential off-targets
4.	Visualize changes in DNA methylation levels around the BACH2 locus using gviz 

