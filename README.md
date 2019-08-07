# UoA - STATS 769 - 2019 S2

## Lab 02

### Copying remote date to local

```
scp -r upi@sc-cer00014-04.its.auckland.ac.nz:/course/Labs/Lab02/ ./
```

### Remote R

Write below R code into a file and name it as `lab02.R` under your personal folder.
```
trips201810 <- read.csv('/course/Labs/Lab02/trips-2018-10.csv')

paste0("Dimension of Trips 201810: (", paste(dim(trips201810), collapse = ', '), ')')
```

Save it and run following command:
```
Rscript lab02.R
```


## Week 1
### About CSV data
Directly load `1988.csv` and `1989.csv`, no need to run `shuf` again. They both contain 10001 lines which means the files have been already pre-processed.

### About `shuf` on Mac
You have to install `shuf` on your Mac: 

```
brew install coreutils
``` 
(Make sure you have installed [brew](https://brew.sh/) already).

Ref: https://apple.stackexchange.com/questions/142860/install-shuf-on-os-x
