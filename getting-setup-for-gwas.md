### Install programs
```
sudo apt-get update
sudo apt-get install -y r-base zlib1g-dev vcftools putty-tools plink
```

### Install packages
```
wget https://cran.r-project.org/src/contrib/Archive/plyr/plyr_1.7.tar.gz
R #capitalizing is important
setwd("/home/ubuntu")
install.packages("plyr_1.7.tar.gz", type="source", repos=NULL)
install.packages("plyr", dependencies = TRUE)
install.packages("dplyr", dependencies = TRUE)
install.packages("stringr", dependencies = TRUE)
install.packages("SKAT", dependencies = TRUE)
install.packages("fdrtool", dependencies = TRUE)
```