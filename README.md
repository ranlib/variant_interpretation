# variant_interpretation
python script to create laboratorian report

```
usage: variant_interpretation [-h] --vcf VCF --bam BAM --bed BED --json JSON --samplename SAMPLENAME [--minimum_coverage MINIMUM_COVERAGE] [--minimum_total_depth MINIMUM_TOTAL_DEPTH]
                              [--minimum_variant_depth MINIMUM_VARIANT_DEPTH] [--minimum_allele_percentage MINIMUM_ALLELE_PERCENTAGE] --report REPORT [--filter_genes] [--filter_variants] [--debug] [--verbose]

variant interpretation

optional arguments:
  -h, --help                                             show this help message and exit
  --vcf VCF, -v VCF                                      annotated vcf file
  --bam BAM, -b BAM                                      annotated vcf file
  --bed BED, -i BED                                      bed file with regions of interest
  --json JSON, -j JSON                                   json file with drug annotation
  --samplename SAMPLENAME, -s SAMPLENAME                 sample name
  --minimum_coverage MINIMUM_COVERAGE                    minimum average coverage in region (default: 0)
  --minimum_total_depth MINIMUM_TOTAL_DEPTH              minimum total number of reads at variant location (default: 0)
  --minimum_variant_depth MINIMUM_VARIANT_DEPTH          minimum number of reads that support variant (default: 0)
  --minimum_allele_percentage MINIMUM_ALLELE_PERCENTAGE  minimum variant allele percentage (default: 0)
  --report REPORT, -r REPORT                             another tsv output file
  --filter_genes, -f                                     output only genes of interest
  --filter_variants                                      take only variants with PASS in vcf filter column
  --debug                                                add debugging information to output
  --verbose                                              turn on debugging output
  ```