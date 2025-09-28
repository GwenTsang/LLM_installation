Ce repo a pour but de compiler des Jupyter Notebooks dans lesquels des LLMs sont installés pour faire des **inférences** .
Ce repo ne contient pas les notebooks ayant pour but de *finetune* le LLM.

La plupart du temps, nous installons les modèles sur :
- Colab gratuit,
- Kaggle gratuit,
- Sur les machines virtuelles proposées sur AWS SageMaker,
- Sur les machines virtuelles proposées par GCP.

Il existe sur Github de nombreux repos qui contiennent des notebooks semblables :

Citons entres autres : 

https://github.com/dvmazur/mixtral-offloading/blob/master/notebooks/demo.ipynb
qui installe une version quantizée de Mixtral-8x7B-Instruct-v0.1


https://github.com/Troyanovsky/Local-LLM-Comparison-Colab-UI/tree/main
qui répertorie de nombreux notebooks installant des LLMs, la plupart du temps avec `cuda` et en passant par une WebUI.
