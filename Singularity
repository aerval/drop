Bootstrap: library
From: nadjakry/default/miniconda:4.8.2

%post
    # install as per gagneurlab/drop
    /miniconda/bin/conda install -y -c conda-forge -c bioconda drop

%runscript
    # run scripts directly from conda env
    exec /miniconda/bin/"$@"
