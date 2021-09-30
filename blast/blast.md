# BLAST practice

### Install BLAST CLI in the VMs

1- Download the executables of BLAST for linux.
```
wget https://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/ncbi-blast-2.12.0+-x64-linux.tar.gz
```

2- Untar and uncompress the file. NOTE: Use `tar` command.

3- Explore the structure of the `ncbi-blast-2.12.0+-x64-linux` directory.

### BLAST CLI

Let's run a `blastp` analysis using the downloaded blast programs from the steps above.

1- Create a directory called `myBlast` and download the sequence `R4GAW5.fasta` in that directory.
```
wget https://www.uniprot.org/uniprot/R4GAW5.fasta
```

2- Prepare the database of blast. NOTE: Use `makeblastdb` and the file `reference_proteins.fasta` located in the blast directory from the repository. NOTE: Do all these steps in the `myBlast` directory. Remember to specified the `path` for the executables.

3- Run a `blastp` with all default values.

4- Run a `blastp` with different values for `E-value`.

5- Explore the options available for the output format in BLAST CLI (i.e. `-outfmt`).

6- Repeat the `blastp` analysis but now only showing in the output the percentage of identity and e-values.

### BLAST Webserver

1- Using the same protein `R4GAW5.fasta` do a `blastp` run but using the webserver of blastp.

2- Explore the following:
- Taxonomy Report
- Graphic Summary
- Distance Tree of results
- Multiple Alignment
- MSA Viewer

3- Which is the "search space" of this run? How these values compare with the run you did in the command line?
