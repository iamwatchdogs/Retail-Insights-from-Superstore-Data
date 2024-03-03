# Retail Insights from Superstore Data

<br>
<div align="center">

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

<br>

[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/iamwatchdogs?tab=repositories&q=&type=public&language=&sort=)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/iamwatchdogs/Retail-Insights-from-Superstore-Data/pulls)
[![GitHub issues](https://img.shields.io/github/issues/iamwatchdogs/Retail-Insights-from-Superstore-Data.svg)](https://github.com/iamwatchdogs/Retail-Insights-from-Superstore-Data/issues)
[![GitHub pull-requests merged](https://badgen.net/github/merged-prs/iamwatchdogs/Retail-Insights-from-Superstore-Data)](https://github.com/iamwatchdogs/Retail-Insights-from-Superstore-Data.js/pulls?q=is%3Amerged)
[![GitHub release](https://img.shields.io/github/release/iamwatchdogs/Retail-Insights-from-Superstore-Data)](https://GitHub.com/iamwatchdogs/Retail-Insights-from-Superstore-Data/releases/)
[![License](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)

</div>
<br>

This is a simple data analysis project where we explore the performance of a superstore by examining various aspects of its sales and profit distribution. After importing and cleaning the dataset, we conducted a descriptive analysis, presenting metadata, regional insights, segment-specific trends, category-wise performance, state-level variations, and ship-mode considerations. Visualizations, ranging from bar plots to pie charts, provided a comprehensive overview of the data. Notable findings include regional disparities in sales and profits, segment-specific performance variations, and distinctions in category-wise sales and profits. The analysis concludes with a consolidated view, emphasizing key insights derived from the diverse explorations. The visual representations and insights can guide strategic decision-making for the superstore, focusing efforts on high-performing regions, segments, and product categories to optimize overall operational efficiency.

## Setting up in your local system

You can start by forking the repo into your profile just by clicking the fork button above or just [click here](https://github.com/iamwatchdogs/Retail-Insights-from-Superstore-Data/fork).

Now, just clone the repo into your local system using the following command:

```bash
git clone https://github.com/<your-github-user-name>/Retail-Insights-from-Superstore-Data.git
```

After cloning the repository, you can navigate through the project in any of the following ways:

- [Using Miniconda environment](#using-miniconda-environment)
- [Jupyter through Anaconda Navigator](#jupyter-through-anaconda-navigator)
- [Google Colab](#using-google-colab)

### Using Miniconda environment

Make sure you have Miniconda using the following command:

```bash
conda --version
```

If you don't have Miniconda installed within your system, then you can just install it from their [official page](https://docs.anaconda.com/free/miniconda/).

You can create a new environment using the dependencies config [`environment.yml`](./environment.yml). Use the following command:

```bash
conda env create -f environment.yml
```

Now that you have created the environment, you have to activate the environment using the following command:

```bash
conda activate retail-insights-from-superstore-data
```

Now you can just use it either in VS code or just host the Jupyter Notebook.

> If you're using the project through VS code you can just selected the Kernel environment as `retail-insights-from-superstore-data`. All you have to do is select
>
> - Select the _"Select Kernel"_ button on the top.
> - Choose _"Python Environment"_ option and choose the conda environment named `retail-insights-from-superstore-data`.

> If you want to host it the Jupyter Notebook, just use the following command:
>
> ```bash
> jupyter notebook
> ```
>
> Now the Jupyter Notebook server is up and running within you system on <localhost:8888>.
> And now, you can access the Jupyter Notebook on <http://localhost:8888/notebooks/retail-analysis.ipynb>.

### Jupyter through Anaconda Navigator

All you have to do is install Anaconda Navigator from the [official website](https://www.anaconda.com/download) and Jupyter Notebook will included within the installation. and all you do is search for Jupyter Notebook within your search utility like the start bar in the Windows. Just start up the Jupyter notebook and navigate through the file location and open the Jupyter notebook.

### Using Google Colab

All you have to do is import this project into [Google colab](https://colab.research.google.com/) and you're done. Just visit their website import the notebook using the GitHub option and you have the whole project within your environment.

