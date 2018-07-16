## Instructions for Installing the Package on Your Own DSVM / DLVM

1. **Requirement**: DSVM/DLVM or a Windows machine with Azure ML Workbench installed.
2. Please clone this repository: `git clone https://github.com/Azure/azureml-tap-notebooks.git`
    - or, click on the green download button ![](imgs/download-gh.PNG)
3. If needed, extract the folder.
4. Open the command prompt in Azure ML: **File > Open Command Prompt**.
5. Navigate to the extracted directory: `chdir <location>\install`
6. If you have a GPU machine with CUDA 8 and CUDNN 5 enabled:
    `pip install tensorflow-gpu==1.6`
    - otherwise:
    `pip install tensorflow==1.6`
7. `setup.bat`
8. Navigate to notebooks: `chdir ..\notebooks`. 
9. Ensure you are in the notebooks directory: `echo %cd%`
    - should be something like (the last two directories are what matter): `C:\Users\alizaidi\Documents\nlpdev\tatk-repos\azureml-tap-notebooks\notebooks`
10. Launch a notebook server `az ml noteboook start`
