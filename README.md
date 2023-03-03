# bedpetools
- A collection of bedpe file operations for HiC-like, or HiChIP data analysis.
- This tool uses [pairtools](https://github.com/open2c/pairtools) and [bedtools](https://github.com/arq5x/bedtools).
- This tool implments some functions@[pairtools], which consider pair format different from bedpe format used in some functions such as pairToBed and pairToPair @[bedtools].
- This tool implements some new algorithms using the above tools.
- We have applied bedpetools algorithms to cluster and visualize HiChIP data [peak3D](https://github.com/hmgene/peaks3d).
## Bedpe and bedpeGraph formats
- read http://genome.ucsc.edu/FAQ/FAQformat#format1
- we define bedpeGraph when bedpe's 7th column represents numeric values
## Selected functions
```
bedpe-cluster 
```
