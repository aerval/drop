Bootstrap: docker
From: continuumio/miniconda3

%post
    # install as per gagneurlab/drop
    /opt/conda/bin/conda install -c conda-forge -c bioconda drop

%runscript
    exec /opt/conda/bin/"$@"
