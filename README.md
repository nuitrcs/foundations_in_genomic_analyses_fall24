# Foundations in Genomic Analyses Fall 2024
This repository is a landing page for the Foundations in Genomic Analyses workshop series held in fall quarter of 2024. This series aims to cover topics and skills foundational to conducting genomics-related research and is a collaboration between Northwestern IT's Research Computing and Data Services and the Galter Library, taught by Haley Carter and Pamela Shaw. 

## Workshop 1: Filetypes and Quality Control 

Sequencing files are a unique type of data that all computational biologists should be comfortable handling. This workshop will cover the structure and use of common sequencing filetypes, including the difference between fasta and fastq, and zipped and unzipped files. We will also work through calculating quality control statistics on these filetypes with fastqc.

Materials can be found here: 

## Workshop 2: Sequence Alignment and Mapping Reads

The first step in almost all bioinformatic pipelines is sequence alignment. There are many software tools available to accomplish this task and choosing the right one and then using it at scale can be intimidating. This workshop will suggest aligners for specific tasks and cover the basics of using each suggested tool including: bwa, bowtie2, hisat2, and minimap2. Participants will compose and run submission scripts for each of these and we will look at the output they create. 

Materials can be found here:

## Workshop 3: Genome Browsers

This workshop provides a brief overview on the most popular features of two genome browsers: the UCSC Genome Browser and the Ensembl Genome Browser. The UCSC Genome Browser was created by the Genome Bioinformatics Group of the University of California at Santa Cruz. Ensembl  is a joint project between EMBL-EBI and the Wellcome Trust Sanger Institute. Both browsers allow the user to retrieve comprehensive information on a gene or genomic sequence in context of the genome, with multiple customizable tracks to display curated data from numerous external sources for features such as polymorphisms, transcript variants and histone modifications. This workshop will cover how to locate these browsers, manage tracks and annotations, how to get sequence data from the browser view, and the avenues to download data from each site – we will compare and contrast how each browser displays data, so the user can decide which is best for their purposes.  
![image](https://github.com/user-attachments/assets/247bb275-965a-4f07-a37d-726cceaf1f3c)


## Workshop 5: 

Materials can be found here: https://github.com/nuitrcs/R_environments_GCC

## Workshop 6: Getting Started with nf-core Nextflow Pipelines

Nextflow is a workflow management tool designed to enable the creation of reproducible workflows that function across computational resources though the use of software containers. Many curated bioinformatics Nextflow pipelines can be found through the nf-core. In this workshop, we will explore their collection and work through running an nf-core pipeline on Quest. The biggest consideration for using Nextflow on Quest is setting the configuration to use Quest’s resources appropriately. We will cover how this is done through the nu-genomics profile for nf-core pipelines as well as writing a custom configuration file when necessary.
