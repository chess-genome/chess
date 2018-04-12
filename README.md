CHESS is a comprehensive set of human genes based on nearly 10,000 RNA sequencing experiments produced by the GTEx project. It includes a total of 21,635 protein-coding genes and 15,985 lncRNA genes. Adding antisense and other RNA genes, release 1.0 of the database contains 39,582 genes and 352,002 transcripts. Of these transcripts, 304,113 represent protein-coding gene isoforms and the rest are noncoding RNAs.

CHESS contains virtually all genes from RefSeq (as of mid-2017) and GENCODE. It adds 1476 protein-coding genes and 1,276 lncRNAs based on strong experimental and alignment evidence, as described in a forthcoming paper (see below).

Colons can be used to align columns.

| Filename  | Content | Description |
| ------------- |:-------------:|:-------------:|
| chess1.0.gff.gz | CHESS gene annotation | This file contains the primary gene set described in the CHESS paper, in GFF format. All genes and transcripts are mapped onto human genome release GRCh38.p7. Included in this file are genes on the reference chromosomes, unmapped scaffolds, assembly patches, and alternate loci. 
| chess1.0.genes | CHESS gene list | This file is a table showing all 39,582 genes in CHESS release 1.0, in a tab-delimited text file with one gene per line. For each gene it provides features such as gene ID, type, gene name, source of the annotation, location(s), GFF ID(s), and a free text description of the gene. |
| chess1.0.protein.fa.gz | CHESS proteins | This FASTA file contains the sequences of all the proteins translated from the CHESS protein-coding genes. For each gene locus that has more than one protein (e.g., splice variants), the longest protein sequence is provided. |
| chess1.0_assembly.gff.gz | Gene annotation for transcriptome assembly | This is a subset of the gene annotation GFF file (chess1.0.gff), containing annotations only on the reference chromosomes and the mitochondrion. It also includes the tRNA and rRNA gene annotations from RefSeq. We recommend using this file with transcriptome assemblers such as StringTie or Cufflinks. |
| chess1.0_and_refseq.gff.gz | CHESS plus RefSeq gene annotations | This is a superset of chess1.0.gff. It adds multiple other gene types annotated in Refseq that are not included in CHESS, such as pseudogenes, V|J|D segements, snoRNAs, snRNAs, telomerase RNAs, guide RNAs, etc. Note that many of these elements (e.g., pseudogenes) are not actually genes, but they are included here for users who want everything in RefSeq plus the additional genes in CHESS. |
