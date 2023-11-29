# Section 1
1) Install Miniconda 23.10.0 on workstation, using information from [conda documentation](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html). <sup>[1]</sup>

2) Conda enables creation of isolated working environments as according to its getting started guide. <sup>[2]</sup>
Hence the project will be contained in the conda virtual environment, myLLMProject, to avoid global side effects.

```
# Syntax for creating a conda working environment.
conda create --name <name of project>

# Without specifying a python version, the default one in Anaconda will be used for virtual env.
conda create --name myLLMProject

# Activate virtual environment
conda activate myLLMProject

# To exit virtual env
conda deactivate
```

## REFERENCES

[1]
“Installing on Linux — conda 23.10.1.dev70 documentation,” docs.conda.io. https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html (accessed Nov. 29, 2023).

‌[2]
“Getting started with conda — conda 4.10.3.post47+e6936a3d documentation,” docs.conda.io. https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html

‌