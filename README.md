# Study of ColE1 expression using public data

## Finding relevant data in short read archive 

we searched [NCBI SRA](https://www.ncbi.nlm.nih.gov/sra) with the following query:

```
((((("escherichia coli"[Organism]) 
  AND "illumina"[Platform]) AND "transcriptomic"[Source]) 
  AND "rna seq"[Strategy]) 
  AND ("2018"[Publication Date] : "2019"[Publication Date]) 
```

## Possible good hit: https://www.ncbi.nlm.nih.gov/bioproject/PRJNA459526

This contains 16 datasets. We downloaded RunInfo table from NCBI and removed columns to produce this:

```

```

## Read processing:

The reads contain the following adapters:

```


```
