CHESS is a comprehensive set of human genes based on nearly 10,000 RNA sequencing experiments produced by the GTEx project. It includes a total of 19,838 protein-coding genes. Adding antisense and other RNA genes, release 3.0 of the database contains 58,516 genes and 158,377 transcripts.

CHESS contains virtually all genes from RefSeq (as of 2022).

| Filename  	| Content 		| Description 	|
| ------------- |:-------------:|:-------------:|
| chess3.0.gff.gz | CHESS gene annotation | This file contains the primary gene set described in the CHESS paper, in GFF format. All genes and transcripts are mapped onto human genome release GRCh38.p12. Included in this file are genes on the reference chromosomes, unmapped scaffolds, assembly patches, and alternate loci.|
| chess3.0.CHM13.gff.gz | CHESS gene annotation on CHM13 | This file contains the primary gene set described in the CHESS paper mapped over to the CHM13 human reference genome, including extra copies of some genes.|
| chess3.0.protein.fa.gz | CHESS proteins | This FASTA file contains the sequences of all the proteins translated from the CHESS protein-coding genes. |
| chess3.0.mapfile.txt |Cross-database transcript ID dictionary| This file provides available mappings between unique transcript identifiers used in the CHESS catalog to unique identifiers in other catalogs (RefSeq,GENCODE) and version 2 of the CHESS catalog. |
| assembled.gtf.gz | Assembled Transcripts | This file contains 987,244 high quality transcripts assembled by StringTie2 from the GTEx dataset and retained after filtering using TieBrush. |

