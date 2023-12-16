# Hirschberg's Algorithm
Implementation by Akanksha Kumar and Sreyansh Mamidi, for Introduction to Bioinformatics at UIUC.

## Overview
This project is an implementation of Hirschberg's algorithm for global alignment. Hirschberg's algorithm uses a dynamic programming approach in order to globally align biological sequences in a space efficient manner.

The algorithm was first published in a 1975 computer science paper by Dan Hirschberg, in which Hirschberg proposed a linear space version of the Needleman-Wunsch algorithm, an existing and prevalent alignment algorithm. Needleman-Wunsch has both a space and time complexity of $O(mn)$, where $m$ and $n$ are the respective lengths of the two sequences being aligned. While Hirschberg's optimizations maintain the $O(mn)$ time complexity, space efficiency is improved to $O(\text{min}\\{m,n\\})$.

## Objectives
1. **Accurate sequence alignment** - First and foremost, our primary goal is to implement Hirschberg's algorithm in a way that _correctly_ and _accurately_ aligns different biological sequences in the most optimal manner. To test correctness, and also to demonstrate the practical use of Hirschberg's algorithm, we will run our implementation and calculate alignments of genomic sequences from various biological domains.
2. **Quantifying space efficiency/memory savings** - Our secondary goal is to analyze the space efficiency of Hirschberg's algorithm, and quantify the memory saved. In order to do so, we will compare Hirschberg's performance with Needleman-Wunsch, on the same input sequences. We will then analyze and illustrate concrete metrics to demonstrate the space efficiency of Hirschberg.

## Installation
For installation, you can simply download the Jupyter notebook included in the repository, `global_alignment.ipynb`, as well as the four corresponding text files with input sequence data. Then, you can open the Jupyter notebook in Google Colab and upload the text files manually by using the navigation bar to the left of the screen. In particular, you can click on the folder icon – followed by the file upload icon – to upload `human_mitochondrion.txt`, `human_tert.txt`, `human_tp53.txt`, and `rickettsiales_bacterium_exercept.txt` into the environment.

## Usage
To run the code in Google Colab, you can click on the play button next to each cell or use Shift+Enter. Any required packages or libraries should be automatically installed and imported. Alternatively, you can run all of the cells at once by selecting _Runtime_ followed by _Run all_.

## Data
For this project, we gathered our input sequence data from the NCBI's Genome Resource. A list of the specific websites where we obtained the data is included below.
1. [Human mitochondrion](https://www.ncbi.nlm.nih.gov/nuccore/NC_012920.1?report=fasta)
2. [Rickettsiales bacteria](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_024304995.1/)
3. [Human TP53 gene](https://www.ncbi.nlm.nih.gov/gene/7157)
4. [Human TERT gene](https://www.ncbi.nlm.nih.gov/gene/7015)

##  Additional Resources
1. https://academic.oup.com/bioinformatics/article/4/1/11/205106
2. https://courses.grainger.illinois.edu/cs466/sp2020/slides/Lecture6_Hirschberg.pdf
3. https://dl.acm.org/doi/10.1145/360825.360861
4. https://www.bionity.com/en/encyclopedia/Hirschberg%27s_algorithm.html
5. https://www.cs.cmu.edu/~ckingsf/class/02-714/Lec07-linspace.pdf
6. https://www.cs.princeton.edu/~wayne/kleinberg-tardos/pdf/06DynamicProgrammingII.pdf
7. https://en.wikipedia.org/wiki/Hirschberg%27s_algorithm
8. https://en.wikipedia.org/wiki/Rickettsiales
9. https://www.frontiersin.org/articles/10.3389/fimmu.2020.589929
