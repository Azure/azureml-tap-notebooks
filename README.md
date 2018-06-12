# Azure ML Text Analytics Package Notebooks

## Instructions for MLADS

1. **Requirement**: DSVM/DLVM or a Windows machine with Azure ML Workbench installed.
1. Please clone this repository: `git clone https://github.com/Azure/azureml-tap-notebooks.git`
    - or, click on the green download button ![](imgs/download-gh.PNG)
1. If needed, extract the folder.
1. Open the command prompt in Azure ML: **File > Open Command Prompt**.
1. Navigate to the extracted directory: `chdir <location>\install`
1. If you have a GPU machine with CUDA 8 and CUDNN 5 enabled:
    `pip install tensorflow-gpu==1.6`
    - otherwise:
    `pip install tensorflow==1.6`
1. `setup.bat`
1. Navigate to notebooks: `chdir ..\notebooks`. 
1. Ensure you are in the notebooks directory: `echo %cd%`
1. Launch a notebook server `az ml noteboook start`

## Useful Links

### [Azure ML Text Analytics Documentation](https://docs.microsoft.com/en-us/azure/machine-learning/service/reference-python-package-overview#azure-ml-package-for-text-analytics)

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
