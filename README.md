# Genetic Ancestry Tool

## Overview
Automate the process of merging genotype data with HapMap using PLINK. 
This automation is done using a python wrapper around PLINK and EIGENSTRAT (linked below).

## Software Dependencies/Requirements
* **Linux/Unix**
* **[Python 3+](https://www.python.org/downloads/)**
* **[PLINK](http://zzz.bwh.harvard.edu/plink/)**
* **EIGENSTRAT (A specific software tool within a larger package, EIGENSOFT) [Download](https://data.broadinstitute.org/alkesgroup/EIGENSOFT/),
 [Code/Examples/Docs](https://github.com/DReichLab/EIG/tree/master/EIGENSTRAT)** 
    * **NOTE: EIGENSTRAT is for Linux only. If you run the application and use EIGENSTRAT, it must be on a Linux 
    machine**

## Main Application Parameters
* `--bfile` _Specify .bed, .bim and .fam._ [Example](http://zzz.bwh.harvard.edu/plink/data.shtml#bed)
* `--bmerge` _Merge in a binary fileset._ [Example](http://zzz.bwh.harvard.edu/plink/dataman.shtml#bmerge)
* `--make-bed` _Make .bed, .fam and .bim._ [Example](http://zzz.bwh.harvard.edu/plink/data.shtml#bed)
* `--out` _Specify output root filename._ [Example](http://zzz.bwh.harvard.edu/plink/data.shtml#plink)
* `--snp_ref` _Specify snp reference file to convert data from SNP IDs to rsIDs._
* `--noweb` _Run PLINK without the internet._ [Example](http://zzz.bwh.harvard.edu/plink/binary.shtml)

# Importing 
To import the project from GitHub, open a terminal session and type only one of either of these commands in the 
directory you want the repository:
~~~
git clone https://github.com/npredey/GeneticAncestryTool.git
git fork https://github.com/npredey/GeneticAncestryTool.git
~~~

## Running the application
##### To run the main applcation (GeneticAncestryTool):
* Navigate to the top level directory `cd ../GeneticAncestryTool`
* 
