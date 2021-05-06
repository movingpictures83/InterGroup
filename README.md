# InterGroup
# Language: Python
# Input: TXT (keyword-value pairs)
# Output: TXT
# Tested with: PluMA 1.1, Python 3.6
# Dependency:

PluMA plugin that returns beta-diversity values between samples within a group
and those in all other groups.

This can be utilized in conjunction with the IntraGroup plugin
to determine the diversity within each group, compared to between groups.

The plugin accepts as input a tab-delimited parameter file of keyword-value
pairs:
mapfile: Mapping of sample names to groups
tsvfile: TSV file of distances (typically unweighted or weighted Unifrac)
group: Target group

Output beta-diversities will appear one-value-per line in a TXT file
