# legumemine
An InterMine containing genomic annotation and expression data for legumes.

LegumeMine is a multi-genus InterMine with a consistent set of data for each genus/species/strain presented:
- general description of each species
- specific description of each strain
- one genome assembly for each strain
- one genome annotation for each strain
- expression data for some strains

The data sources used to load LegumeMine are therefore limited:
- lis-about - data from the "about_this_collection" files describing the species and strains
- lis-fasta - assembly, CDS, protein, and transcript FASTAs for a given assembly/annotation (gnm#.ann#)
- lis-gff - gene_models_main GFF file with genes and child features
- lis-ipr-gff - Interpro scan data in GFF format
- lis-gfa - gene family associations for genes and proteins
- lis-pathway	- pathway associations for genes
- lis-expression - gene expression data
- lis-genefamily - the gene family definitions  
- lis-phylotree - the gene family trees
- interpro - Interpro data
- interpro-go - Interpro-GO term relations
- go - GO terms
- so - SO terms
- obo - plant-ontology
- obo - plant-trait-ontology
