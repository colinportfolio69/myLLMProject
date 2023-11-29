# Section 1
1) Reading source: https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html
Miniconda 23.10.0 was installed on linux machine.

2) Reading source: https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html
Conda enables creation of isolated working environments.
Hence the project will be contained in a python3 virtual environment named myLLMProject, to avoid global side effects.

```
# Syntax for creating a conda working environment.
conda create --name <name of project>

# Without specifying a python version, the default one in Anaconda will be used for virtual env.
conda create --name myLLMProject

# Activate virtual environment
conda activate myLLMProject

# exit virtual env
conda deactivate
```

