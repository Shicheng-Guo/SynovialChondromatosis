

```
gatk StructuralVariationDiscoveryPipelineSpark \
     -I input_reads.bam \
     -R reference.2bit \
     --aligner-index-image reference.img \
     --kmers-to-ignore kmers_to_ignore.txt \
     --contig-sam-file aligned_contigs.sam \
     -O structural_variants.vcf
```
