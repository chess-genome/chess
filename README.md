CHESS is a comprehensive set of human genes based on nearly 10,000 RNA sequencing experiments produced by the GTEx project. It includes a total of 20,352 protein-coding genes and 18,887 lncRNA genes. Adding antisense and other RNA genes, release 2.1 of the database contains 42,611 genes and 323,258 transcripts. Of these transcripts, 266,331 represent protein-coding gene isoforms and the rest are noncoding RNAs.

CHESS contains virtually all genes from RefSeq (as of mid-2017) and GENCODE. It adds 224 protein-coding genes and 2,671 lncRNAs based on strong experimental and alignment evidence, as described in a forthcoming paper (see below).

| Filename  	| Content 		| Description 	|
| ------------- |:-------------:|:-------------:|
| chess2.1.gff.gz | CHESS gene annotation | This file contains the primary gene set described in the CHESS paper, in GFF format. All genes and transcripts are mapped onto human genome release GRCh38.p8. Included in this file are genes on the reference chromosomes, unmapped scaffolds, assembly patches, and alternate loci.|
| chess2.1.genes | CHESS gene list | This file is a table showing all 42,611 genes in CHESS release 2.1, in a tab-delimited text file with one gene per line. For each gene it provides features such as gene ID, type, gene name, source of the annotation, location(s), GFF ID(s), and a free text description of the gene. |
| chess2.1.protein.fa.gz | CHESS proteins | This FASTA file contains the sequences of all the proteins translated from the CHESS protein-coding genes. For each gene locus that has more than one protein (e.g., splice variants), the longest protein sequence is provided. |
| chess2.1_assembly.gff.gz | Gene annotation for transcriptome assembly | This is a subset of the gene annotation GFF file (chess2.1.gff), containing annotations only on the reference chromosomes and the mitochondrion. It also includes the tRNA and rRNA gene annotations from RefSeq. We recommend using this file with transcriptome assemblers such as StringTie or Cufflinks. |
| chess2.1_and_refseq.gff.gz | CHESS plus RefSeq gene annotations | This is a superset of chess2.1.gff. It adds multiple other gene types annotated in Refseq that are not included in CHESS, such as pseudogenes, V_segements,C_segements,D_segements,J_segements, snoRNAs, snRNAs, telomerase RNAs, guide RNAs, etc. Note that many of these elements (e.g., pseudogenes) are not actually genes, but they are included here for users who want everything in RefSeq plus the additional genes in CHESS. |

### Summary

|  					  | genes | transcripts |
|---------------------|:------|:------------|
|protein_coding       | 20352 | 266331      |
|lncRNA 	          | 18887 | 49892		|
|other		          | 3372  | 7035        |
|total                | 42611 | 323258		|
|novel_protein_coding | 224   |	317 		|
|novel_lncRNAs 		  | 2671  |	3333 		|
