<!-- dx-header -->
# SNP and Indel Evaluator (DNAnexus Platform App)

takes a gold snp set, bam, and vcf to evaluate for sens/spec  
  
This DNA Nexus App wraps a standalone python version of the evaluator that can be used without DNANexus  
  
usage: standalone_accuracy_evaluator.py [-h] [--bed_file BED_FILE]  
[--bam_file BAM_FILE]  
[--ref_vcf REF_VCF]  
[--eval_vcf EVAL_VCF]  
[--ref_fasta REF_FASTA]  
  
Take in a high quality snp/indel set and evaluate a call set for concordance  
  
optional arguments:  
-h, --help            show this help message and exit  
--bed_file BED_FILE   bed file to limit comparisons to certain regions-  
optional  
--bam_file BAM_FILE   bam file to use to get readcounts for missing sites  
--ref_vcf REF_VCF     file of SNPs or INDELs you know to be true in your  
callset  
--eval_vcf EVAL_VCF   file of SNPs and/or INDELs you want to compare to the  
known true callset  
--ref_fasta REF_FASTA  
reference fasta used to call the bam  
  


This is the source code for an app that runs on the DNAnexus Platform.
For more information about how to run or modify it, see
https://wiki.dnanexus.com/.
<!-- /dx-header -->

Evaluates any vcf generated from data that has a trusted set of snps for accuracy, and generates lists of missed variants

<!--
TODO: This app directory was automatically generated by dx-app-wizard;
please edit this Readme.md file to include essential documentation about
your app that would be helpful to users. (Also see the
    Readme.developer.md.) Once you're done, you can remove these TODO
comments.

For more info, see https://wiki.dnanexus.com/Developer-Portal.
-->
