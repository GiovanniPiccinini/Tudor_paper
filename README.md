# Tudor_paper

In the main directory there are the sequences of all T3 domains of OG164

### Dir ML_trees:
IQTREE outputs for the 10 ML replicates + topology evaluation file. Replicates considered in the paper are rooted. For the three replicates excluded, the raw IQTREE output is present.
Within, the # Dir 
  
### Dir HMM_profiles:
HMM profiles for each OG used to build the distance matrix for the NJ tree
  
###  Dir Alignments:
Single-OG alignments, comprehending all sequences before subsampling (see Materials and Methods). All alignments were later merged and realigned altogether with MAFFT-DASH, previous to ML tree inference (except for OG164 subclades, that were excluded from the ML inference)

### Dir OG164
Raw fasta file of the OG164 as outputted by OrthoFinder + whole sequence alignment and tree inference to feed DISCO with + DISCO output subclades

### Dir Ichthyosporea_T3-Piwi_analyses
T3-containing Ichthyosporea proteins (both I. hoferi and C. perkinsii), all sequences of the Piwi-like OG that contained a Piwi domain, a directory containing the 20 trees used for the I.hoferi-OG164 topology tests, and a directoy containing the 40 trees used for the Piwi+PAZ topology tests
