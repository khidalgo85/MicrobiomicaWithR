
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

[![ForTheBadge
built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/Naereen/)
<!-- badges: end -->

# Explorando microbiomas com R <img src="imgs/gemm-hex.png" align="right" width = "120px"/>

O R é uma linguaguem muito versátil, que é amplamente usada em
diferentes áreas. Este tutorial apresenta as principais funções do
pacote [Phyloseq](https://joey711.github.io/phyloseq/) para a análises
de microbiomas, principalmente a partir das saída do processamento das
sequencias em [qiime2](https://qiime2.org/). Em conjunto com **ggplot2**
é possível construir diversos gráficos para caracterizar e visualizar
microbiomas.

## Análise de microbiomas

<img src="imgs/analises.png" align="center" width = "100%"/>

Neste tutorial os principais pacotes usados são:

<img src="imgs/qiime2R.png" width = "120px"/>
<img src="imgs/phyloseq-hex.png" width = "120px"/>
<img src="imgs/ggplot2-hex.png" width = "120px"/>

## Instalação

-   `qiime2R`: Pode ser instalado a partir de `devtools`

<!-- -->

    ## Instala o pacote qiime2R que lê arquivos .qza (saída do QIIME2)
    if (!requireNamespace("devtools", quietly = TRUE)){install.packages("devtools")}
    devtools::install_github("jbisanz/qiime2R", force = TRUE)

-   `phyloseq`: pode ser instalado a partir de `BiocManager`

<!-- -->

    ## Instala phyloseq
    if (!requireNamespace("BiocManager", quietly = TRUE))
        install.packages("BiocManager")
    BiocManager::install("phyloseq")

-   `ggplot2`: é instalado diretamente desde o CRAN

<!-- -->

    ## Instala ggplot2
    install.packages("ggplot2")

## Uso

Os pacotes pode ser carregados como qualquer outro pacote de R:

    library(qiime2R)
    library(phyloseq)
    library(ggplot2)

O tutorial completo se encontra [aqui](https://bit.ly/36SpwzO)
