# flex_probe_design

Repository storing code for the design of custom Flex Short Gapfill probes.
Design follows recommendations from 10x genomics, as described below.

### Implemented design rules:
- GC content should be between 44 − 72% for each 25 bp probe half.
- Avoid homopolymer repeats.
- Avoid overlap with annotated repeat or low complexity sequences.
- If possible, design probes for coding regions of mRNA as opposed to untranslated regions.

### Additional checks, which are currently done manually (will automate in the future):
- Avoid known common SNPs at the ligation junction - use UCSC Genome Browser and the Single Nucleotide Polymorphism Database (dbSNP) to check. If avoiding SNPs is not possible, SNPs and mismatches should be at least four bp away from the ligation junction.

[TO DO: CONTINUE ADDING RULES FROM 10X HERE]


