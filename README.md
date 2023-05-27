# Details on Files

In order of how they are run with a description

1. GFF_and_Fasta_Download.Rmd - Downloading release 56 version of GFF and Fasta files of Ascomycota Phylum
2. Processing for GFF and Fasta Organisation.ipynb - Creating a npy file list containing all the organisms downloaded from before for organisation purposes
3. Code blocks starting with 'Preprocessing' are the code blocks extracting information from the fasta and gff files for the neural network (Note: Previewing code may require multiple refreshes due to memory constraints) - the descripters following are for the species you want to analyse for (single, multiple, or replaced with a GFP sequence)
