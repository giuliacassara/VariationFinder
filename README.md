# VariationFinder
A re-implementation in Python3 of the open source project MutationFinder for gene mutation detection in free text http://mutationfinder.sourceforge.net/

## Features

* Recognizes WNM, RSID and c.Na>a genomic variant notations, including natural language forms 
* More genomic variant notations will be added later, based on this table https://academic.oup.com/view-large/206216442

## Usage

from the terminal type:

```
./mutation_finder.py corpora/test_set.txt 

```

Output file is test_set.txt.mf in the same directory of mutation_finder.py

## References

```
MutationFinder: A high-performance system for extracting point mutation mentions from text
J. Gregory Caporaso, William A. Baumgartner Jr., David A. Randolph, K. Bretonnel Cohen, and Lawrence Hunter; Bioinformatics, 2007 23(14):1862-1865; doi:10.1093/bioinformatics/btm235;
```

