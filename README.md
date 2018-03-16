# Azure Machine Learning Service #
This Repo is going to show all things related to Azure Machine Learning Service

## Pre-requisite ##
* Azure Global Account for [Azure Portal](https://portal.azure.com) . For those who don’t have one, you can apply it [here](https://azure.microsoft.com/zh-cn/free/)
* Install AML Workbench following the [documentation](https://docs.microsoft.com/en-us/azure/machine-learning/preview/quickstart-installation)
* Visual Studio Code: download and install VS code [here](https://code.visualstudio.com/)
* Python (3.5.2) environment on your local computer installed by Workbench
* Create Ubuntu-based DSVM on Azure [here](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft-ads.linux-data-science-vm-ubuntu)
* Create HDInsight for Spark cluster on Azure [here](https://azuremarketplace.microsoft.com/zh-cn/marketplace/apps/Microsoft.HDInsightCluster)
* (Optional) AML Workbench Simple Demo:
> 1. [Prepare Data](https://docs.microsoft.com/en-us/azure/machine-learning/preview/tutorial-classifying-iris-part-1)
> 2. [Build Models](https://docs.microsoft.com/en-us/azure/machine-learning/preview/tutorial-classifying-iris-part-2)
> 3. [Deploy Models](https://docs.microsoft.com/en-us/azure/machine-learning/preview/tutorial-classifying-iris-part-3)
> 4. [Work with Python IDE (especially VS Code)](https://docs.microsoft.com/en-us/azure/machine-learning/preview/how-to-configure-your-ide)
> 5. [Train Model on local or Azure GPU](https://docs.microsoft.com/en-us/azure/machine-learning/preview/how-to-use-gpu)
> 6. [Use DSVM or Spark for training](https://docs.microsoft.com/en-us/azure/machine-learning/preview/how-to-create-dsvm-hdi)
> 7. [Use Visual Studio Tools for AI](https://docs.microsoft.com/en-us/azure/machine-learning/preview/quickstart-visual-studio-tools)
> 8. [Use Visual Studio Code Tools for AI](https://docs.microsoft.com/en-us/azure/machine-learning/preview/quickstart-visual-studio-code-tools)

## AI Hackfest Scope ##
![Azure Machine Learning Suite](/img/Azure Machine Learning Suite.png)

Our AI POC Hackfest would go through the full process of AI Model building and deploying, with the help of MS AI Technology, including:
* Configure Experimentation (AML Workbench and Python installation and configuration are not included, please do it before the hackfest)
* Data Preparation and Data Wrangling
* Building ML or DNN model with tools or DL framework, such as CNTK, TF, Keras, …
* Training Model on local PC and on Azure, leveraging GPU Resources/Spark
* Deploying Model to web service
