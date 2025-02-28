# Tudor_paper


### Dir ML_trees:
Tudor domain trimmed alignment + IQTREE outputs for the 10 ML replicates + topology evaluation file. Replicates considered in the paper are rooted. For the three replicates excluded, the raw IQTREE output is present.
The Directory "Profile-to-sequences_HMMsearch_for_subsamples_selection" contains the hmm-to-fasta alignments used to subsample the 50% of sequences more similar to the profile in order to ease tree inference. 
  
### Dir HMM_profiles:
HMM profiles for each OG used to build the distance matrix for the NJ tree.
  
###  Dir Alignments:
Single-OG alignments, comprehending all sequences before subsampling (see Materials and Methods). All alignments were later merged and realigned altogether with MAFFT-DASH, previous to ML tree inference (except for OG164 subclades, that were excluded from the ML inference).
\n In this directory is also present, for each OG, a sub-directory containing the raw OG.fasta file (raw output of OrthoFinder), the InterProScan annotation of it, and the output file of the custom Tudor domain extraction (script domain_extraction.sh provided).

### Dir OG164
Raw fasta file of the OG164 as outputted by OrthoFinder + tree inference .iqtree output to feed DISCO with + DISCO output subclades.

### Dir Ichthyosporea_T3-Piwi_analyses
T3-containing Ichthyosporea proteins (both I. hoferi and C. perkinsii), all sequences of the Piwi-like OG that contained a Piwi domain, a directory containing the 20 trees used for the I.hoferi-OG164 topology tests, and a directoy containing the 40 trees used for the Piwi+PAZ topology tests.

### Dir Metazoa_tree_for_PICs
Contains alignment file and output of RAxML branch length optimization on the Metazoa tree (built from references in Extended_referenced.pdf) used to calculated Phylogenetic Independent Contrasts for statistical analyses
