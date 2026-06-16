README for the real data used in the analysis

Dataset source:
The real dataset used in this study was downloaded from the NCBI Gene Expression Omnibus (GEO) database:
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE5680

Dataset description:
This dataset contains RNA microarray measurements from the eyes of 120 F2 rats, originally reported by Scheetz et al. (2006). The raw dataset contains more than 31,000 probes.

Preprocessing:
Before the independence analysis, probes with weak expression signals or limited variability were removed. Specifically, a probe was retained if:

1. Its maximum expression level across the 120 rats exceeded the first quartile of all RMA expression values.
2. It exhibited at least a two-fold change in expression among the 120 rats.

After preprocessing, 18,986 probes remained for subsequent analysis.

File description:
probe_ids.txt
This file contains the probe IDs of the 18,986 probes retained after preprocessing.

Reference:
Scheetz, T. E., Kim, K. Y. A., Swiderski, R. E., Philp, A. R., Braun, T. A., Knudtson, K. L., Dorrance, A. M., DiBona, G. F., Huang, J., Casavant, T. L., et al. (2006). Regulation of gene expression in the mammalian eye and its relevance to eye disease. Proceedings of the National Academy of Sciences, 103, 14429–14434.
