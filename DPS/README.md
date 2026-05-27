# DPS

DPS is a data repo for the manuscript entitled "Detecting poliovirus sequences in the Sequence Read Archive database using bioinformatics tools". 

The Figures folder contains excel files of total non-deduplicated alignments made between the non-poliovirus genomes in the RefSeq database to the capsid region of poliovirus genome segments using BLASTn. Also included is an R file containing the figure-generation codes for Figures 1 and 2. The bac_sum_removal excel file shows the bacterial RefSeq entries removed from Figure 1 and 2 results due to potential contamination. The first tab gives submission information for each entry. The second tab shows the original blastn results when aligning non-poliovirus genomes to the capsid region of poliovirus genome segments. The third tab shows BLASTn results after aligning the bacterial entries to the nucleotide database from NCBI. 

The Simulation_alignment folder has alignment count results using BLASTn, Bowtie2, Magic-BLAST, MegaBLAST, and Elastic BLAST to align simulated reads of all viral RefSeq non-poliovirus genomes and poliovirus genomes at 10x coverage and lengths of 100, 150, 200, and 250 base pairs using the complete genomes of poliovirus serotypes 1, 2, and 3 as a reference. The reference fasta files to create the simulated reads for the viral RefSeq non-poliovirus genomes is labeled refseq_wopolio.fasta. The reference fasta file used to create the poliovirus genomes is labeled sabin.fasta.

The STAT folder contains STAT query results for Enterovirus, Enterovirus C, and the Poliovirus serotypes 1, 2, and 3 in the excel file labeled STAT_query_results. The accessions and study information used as control accessions for the STAT queries is in excel file labeled stat_control.

## Status

Under development — documentation in progress.

---

See the [PASS root README](../README.md) for an overview of all affiliated projects.
