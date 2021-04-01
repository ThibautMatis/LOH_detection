# LOH_detection
Contient FACETS


**# Install cnv_facets with bioconda :"conda install cnv_facets", works with R
# Input 1 [-t] :  Tumor.bam
# Input 2 [-n] : Normal.bam
# Input 3 [vcf] : Common_SNP_list.vcf.gz
# output [-o] : Folder with graph and VCF
# -- gbuild : reference choosen, hg19
**
cnv_facets.R -t /data/Bam_data/Tumor/tumor.bam -n /data/Bam_data/Blood/normal.bam -vcf /data/Reference/targeted.vcf.gz -o /data/cnv-facets/output_file --gbuild hg19
