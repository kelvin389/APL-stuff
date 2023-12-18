# APL stuff
Some APL functions written for school assignments. Each function has both a direct and tacit version (tacit indicated by \_t suffix) that work identically.

### count
Count number of each DNA nucleotide in a given string (ACGT)

```
    count 'ACTGATACGTACTGCATCGATTGTGTGATGTGAGTAGATCCGATGTACGTAGT'
13 8 15 17
    count 'HELLOWORLD'
0 0 0 0
```


### gc
Determine what percentage of a string consists of the letters 'C' or 'G"
```
    gc 'GCCGGCGCGCGCG'
100
    gc 'ASDF'
0
    gc 'ACGT'
50
```

### magic
Determine whether an array is a magic square. A magic square is defined as a square array of numbers such that each column, row, and both main diagonals all sum to the same number
```
    magic 1 1⍴42
1
    magic 3 3⍴4 9 2 3 5 7 8 1 6
1
    magic 2 2⍴1 2 3 4
0
```