# CLI Practice

When in doubt remember to check the manual pages from the commands (e.g. `man ls`). Also, use google and the many resources available online.

NOTE: There are many ways to resolve some of the tasks below. Use the one that suits you the best unless a specific method is mention.

## Moving between directories

1- Go to your home directory

2- List all the contents of the home directory

3- List again the content but information about the permissions

4- List and sort the content by date.

NOTE: Use only the `ls` command.

## Creating and removing directories

1- Create a directory named: cli

2- Inside the directory create three directories named:
```
ex1
ex2
ex3
ex34
```

3- Erase the directory named: `ex3`

4- Rename directory `ex34` to `ex3`

5- Go to the home directory and create multiple nested directories in one command. Result should look like:
```
$HOME/test/cl1/practice
```

6- Erase the `$HOME/test` directory

## Copy and move files

1- In the `cli` directory create a file named: `species.txt`

2- Open the file with a text editor and paste the following:
```
Escherichia coli
Saccharomyces cerevisiae
Arabidopsis thaliana
Caenorhabditis elegans
Drosophila melanogaster
Danio rerio
Mus musculus
Homo sapiens
```

3- Save the file

4- Create a copy of the file and name it: `species_copy.txt`

5- Create a directory named `backup` and move the file `species_copy.txt` to that directory.

NOTE: Move the file witout changing directories

## Clonning a repository

1- Clone the repository to be used in the other exercises
```
git clone https://github.com/rivera10/bash.git
```

2- Enter the directory `bash/practice` to do the following exercises


## Opening a file

1- Use `less` to explore the file `sequence.gp`

2- Use `head` to get the first 7 lines from file `sequence.gp`

3- use `cat` to open the entire file in the command line

## Grep

1- Use `grep` to get the sequence named `example_fasta_2` from the file `example.fasta`

2- Repeat the same command now but make sure the include the nucleotide sequences

NOTE: Use the `man` and look for the options `-A and -B`


3- Extract the sequence named `example_fasta_3` inclduing all the nucleotides and store the results in a new file named `mysequence.fasta`

NOTE: Use `less` to know how many lines you need to extract


## Cut

1- Use the file `species.txt` and cut the first column


2- Use the file
