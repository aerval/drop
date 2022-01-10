Bootstrap: docker
From: continuumio/miniconda3

%post
    /opt/conda/bin/conda install -y -c conda-forge -c bioconda drop

%runscript
    # run scripts directly from conda env
    exec /opt/conda/bin/"$@"
