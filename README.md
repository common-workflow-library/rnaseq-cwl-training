
# Downloading reference data

```
mkdir rnaseq
cd rnaseq
wget --mirror --no-parent --no-host --cut-dirs=1 https://download.pirca.arvadosapi.com/c=pirca-4zz18-sa9s62lzc00jeds/
```

# Building the Docker image

```
cd dockerfile
docker build -t cwl-training-rnaseq-tools .
```

# Acknowledgements

These CWL lessons are based on "Introduction to RNA-seq using
high-performance computing (HPC)" lessons developed by members of the
teaching team at the Harvard Chan Bioinformatics Core (HBC) and
obtained from

https://github.com/hbctraining/Intro-to-rnaseq-hpc-O2

The original lessons are open access materials distributed under the
terms of the Creative Commons Attribution license (CC BY 4.0), which
permits unrestricted use, distribution, and reproduction in any
medium, provided the original author and source are credited.