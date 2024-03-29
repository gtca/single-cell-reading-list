# Single-cell reading list

A curated selection of blog posts on single-cell data analysis. This list is a (constant) work in progress.

The creation of this list was inspired by [Gopher Reading List](https://github.com/enocom/gopher-reading-list).

## Start here

- [Analysis of single-cell RNA-seq data course](https://hemberg-lab.github.io/scRNA.seq.course/index.html)

- [Introduction to single-cell RNA-seq technologies](https://liorpachter.wordpress.com/2019/02/19/introduction-to-single-cell-rna-seq-technologies/) with [slides here](https://figshare.com/articles/Introduction_to_single-cell_RNA-seq_technologies/7704659/1)

- [Orchestrating single-cell analysis with bioconductor](https://osca.bioconductor.org/)

- [Current best practices in scRNA-seq data analysis](https://www.embopress.org/lookup/doi/10.15252/msb.20188746) paper (Mol Syst Biol 2019)

- [Tutorial: guidelines for the computational analysis of single-cell RNA sequencing data](https://www.nature.com/articles/s41596-020-00409-w) paper (Nature Protocols 2020)

- [Next-generation computational tools for interrogating cancer immunity](https://www.nature.com/articles/s41576-019-0166-7) paper (Nature Genetics Reviews 2019)

### Videos

- [scRNA-seq analyses: challanges, opportunities, and best practices (2020)](https://www.youtube.com/watch?v=q--Hr9ZOpH4) primer by Stephen Fleming (Broad Institute)

## Beginner

- [On stabilizing mean-variance relationship in scRNA-seq data](http://www.nxn.se/valent/2017/10/15/variance-stabilizing-scrna-seq-counts)

### Benchmarks

- [Batch correction methods](https://www.biorxiv.org/content/10.1101/2020.05.22.111211v2) (2020), also see [the GitHub repository](https://github.com/cellgeni/batchbench)

- [Data integration methods](https://www.biorxiv.org/content/10.1101/2020.05.22.111161v2) (2020), also see [the GitHub repository](https://github.com/theislab/scib)

- [Systematic comparison of single-cell and single-nucleus RNA-sequencing methods](https://www.nature.com/articles/s41587-020-0465-8) (2020), also see [the Bitbucket repository](https://bitbucket.org/jerry00/scumi-dev/src/master/)

- [Over 1000 tools reveal trends in the single-cell RNA-seq analysis landscape](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02519-4) (2021)

## Intermediate

- [Unique Molecular Identifiers – the problem, the solution and the proof](https://cgatoxford.wordpress.com/2015/08/14/unique-molecular-identifiers-the-problem-the-solution-and-the-proof/)

- [Comment](https://www.charite-bioinformatik.de/publikationen_science_comment2017.php) on [Villani2017](http://science.sciencemag.org/content/356/6335/eaah4573) paper in Science about new types of dendritic cells and monocytes in human blood

- [Common pitfalls when clustering biological data](https://stke.sciencemag.org/content/9/432/re6) paper

- [Droplet scRNA-seq is not zero-inflated](https://www.nature.com/articles/s41587-019-0379-5) (2020) and [UMI or not UMI, that is the question for scRNA-seq zero-inflation](https://www.nature.com/articles/s41587-020-00810-6) (2021)

- [Separating measurement and expression models clarifies confusion in single-cell RNA sequencing analysis](https://www.nature.com/articles/s41588-021-00873-4) (2021), which highlights the importance of disentangling _expression_ and _measurement_ models, and states that a _Poisson measurement model_ is usually the most appropriate one to use

- [Equivalence classes](http://mcmero.github.io/blog/Equivalence-classes/) in RNA-seq analyses

- [Normalization and variance stabilization](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1874-1) and [analytic Pearson residuals](https://www.biorxiv.org/content/10.1101/2020.12.01.405886) for scRNA-seq data

- [Transformation and preprocessing](https://www.biorxiv.org/content/10.1101/2021.06.24.449781) of scRNA-seq data.

## Advanced

- [Linking scRNA-seq to scDNA-seq data](https://kieranrcampbell.github.io/blog/2018/11/13/clonealign.html) by Kieran Campbell

- [Low Rank Approximation of Kernels](https://twitter.com/GCLinderman/status/1094997866106507264) — intuition behind [FIt-tSNE](https://www.nature.com/articles/s41592-018-0308-4). Also see [this paper](https://arxiv.org/abs/1902.05804) about revealing fine-grained structure by adjusting degree of freedom

- [RNA velocity of single cells](https://www.nature.com/articles/s41586-018-0414-6) (2018) and [dynamic modelling with scVelo](https://www.nature.com/articles/s41587-020-0591-3) (2020)

- [Optimizing expression quantitative trait locus mapping workflows for single-cell studies](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02407-x) (Genome Biology 2021)

### Autoencoders

- [Count based autoencoders and the future for scRNA-seq analysis](http://www.nxn.se/valent/2018/4/20/count-based-autoencoders-and-the-future-for-scrna-seq-analysis) by Valentine Svensson

- [Why variational autoencoders pursue PCA directions](https://arxiv.org/abs/1812.06775)

### Multi-omics

- [Single-cell multiomics: technologies and data analysis methods](https://www.nature.com/articles/s12276-020-0420-2) review (2020)

## Other lists

- [awesome-single-cell](https://github.com/seandavi/awesome-single-cell)

- [awesome-multi-omics](https://github.com/mikelove/awesome-multi-omics)
