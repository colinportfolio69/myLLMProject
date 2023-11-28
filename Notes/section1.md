# Section 1
1) Due to the hard disk of the workstation used for this project being encrypted, most of the testing will take place in a VMware virtual machine running a linux Host OS. (Installation of anaconda proves to be impossible with encrypted hard disk.)

2) The github repo is set as a shared folder between Host OS, mintllm and Guest OS. VMware's shared folders are found in:
```
/mnt/hgfs
```

3) In the VM, named mintllm, anaconda version 2.5.1 was installed.

4) Reading source: https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html
Anaconda enables creation of isolated working environments.
Hence the project will be contained in a python3 virtual environment named myLLMProject, to avoid global side effects.

```
# Syntax for creating a conda working environment.
conda create --name <name of project>

cd /mnt/hgfs/myLLM/

# Without specifying a python version, the default one in Anaconda will be used for virtual env.
conda create --name myLLMProject

# Activate virtual environment
conda activate myLLMProject

# exit virtual env
conda deactivate
```

