1) Python library dependencies were installed. Matplotlib for visualization of data, Numpy for data organization e.g. arrays, pylzma compression algorithm, ipykernel for importing Google Colab GPU in order to train data with cuda and jupyter notebook for recording progress.

```
pip3 install matplotlib numpy pylzma ipykernel jupyter
```

2) Install python3's pytorch API library. PyTorch is a framework renowned for utilizing GPUs and CPUs for machine learning projects.
Based on the following section in the Pytorch documentation, the cuda cores from Google Colab's GPU can be imported into the conda working environment by the following command:

![Alt text](../img/screnshot_PyTorch_Build.png)

```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```