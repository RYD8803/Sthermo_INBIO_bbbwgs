# Overview
This project were aimed to analyzed three Streptococcus thermophilus strain (CF2_14, CF8_14, CF13_14) to find any SNP unique to each strain and to distinguish strain-specific SNPs in order to identify unique genetic characteristics of each strain.

# Workflow
- Data Retrieval  
- Reads Quality Check and Cleaning
- Alignment to Reference Genome
- Converting data and Sorting
- Variant Calling and Annotation

# Tools used
- Quality check: FastQC(v0.12.1)
- Trimming low quality reads and adapters: fastp (v1.3.4)
- Alignment: bwa (v0.7.19-r1273)
- Converting, sorting and indexing: samtools (v1.23.1)
- Variant calling: Freebayes (v1.3.10)
- Annotation: snpEff (v5.4c), bcftools (v1.19)
- Visualization: ngi-visualization (v0.1)
- Data processing: R (v4.5.1)

## Data Retrieval
Retrieved from NCBI-SRA using SRA Toolkit prefetch (v3.4.1).

*S. thermophilus CF2_14* [SRR5310876](https://www.ncbi.nlm.nih.gov/sra/SRR5310876) 

*S. thermophilus CF8_14* [SRR11910258](https://www.ncbi.nlm.nih.gov/sra/SRR11910258) 

*S. thermophilus C13_14* [SRR11910376](https://www.ncbi.nlm.nih.gov/sra/SRR11910376) 

All SRA data were provided through BioProject [PRJNA336518](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA336518) (Barnaba 2022).

# Reference
Barnaba TJ, Gangiredla J, Mammel MK, Lacher DW, Tartera C.2022. Draft genome sequences of 18 Streptococcus  strains isolated from live dietary supplements and cultured food products. Microbiol Resour Announcment. 11:e00266-22. DOI: https://doi.org/10.1128/mra.00266-22.

Dan T, Hu H, Tian J, He B, Tai J, He Y. 2023. Influence of Different Ratios of Lactobacillus delbrueckii subsp. bulgaricus and Streptococcus thermophilus on Fermentation Characteristics of Yogurt. Molecules. 28(5): 2123. DOI: https://doi.org/10.3390/molecules28052123 

Kalnins A, Otto K, Rüther U, Müller-Hill B. 1983. Sequence of the lacZ gene of Escherichia coli. The EMBO journal. 2(4): 593–597. DOI: https://doi.org/10.1002/j.1460-2075.1983.tb01468.x

Kondo K, Wakabayashi S, Yagi T, Kagamiyama H. 1984, The complete amino acid sequence of aspartate aminotransferase from Escherichia coli: sequence comparison with pig isoenzymes. Biochem Biophys Res Commun. 122(1):62-67. DOI: 10.1016/0006-291x(84)90439-x

Lemaire HG, & Müller-Hill B. 1986. Nucleotide sequences of the galE gene and the galT gene of E. coli. Nucleic acids research. 14(19): 7705–7711. DOI: https://doi.org/10.1093/nar/14.19.7705.

Miles JS, & Guest JR. 1984. Nucleotide sequence and transcriptional start point of the phosphomannose isomerase gene (manA) of Escherichia coli. Gene. 32(1-2): 41–48. DOI: https://doi.org/10.1016/0378-1119(84)90030-1.

Siddiqi M, Tarrah A, Chen Z-H, LaPointe G. 2024. Phenotypic Differentiation of Streptococcus thermophilus and Lactobacillus delbrueckii subsp. bulgaricus Isolates Found in Yogurt Starter Cultures. Fermentation. 2024; 10(12):601. DOI: https://doi.org/10.3390/fermentation10120601



