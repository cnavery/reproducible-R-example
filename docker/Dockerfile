FROM rocker/tidyverse:4.0.2
LABEL maintainer="cansav09@gmail.com"
WORKDIR /rocker-build/

FROM condaforge/mambaforge
 
 RUN conda config \
     --add channels defaults \
     --add channels bioconda \
     --add channels conda-forge
 
 RUN conda install -y samtools
