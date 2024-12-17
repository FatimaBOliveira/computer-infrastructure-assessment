# Computer Infrastructure Assessment

This repository contains my work for the module Computer Infrastructure in the Higher Diploma in Science in Computing in Data Analytics course, [ATU Galway Mayo](https://www.gmit.ie/).

![command-line interface](img/G2CI.png) 

*Image taken from [G2](https://www.g2.com/articles/command-line-interface)*

This README follows the instructions from [GitHub](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) on how to write README files.

## About this project

 This repository contains the following:
 - a notebook, [weather.ipynb](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/blob/main/weather.ipynb), explaining how to use a shell, how to complete the tasks and project;
 - directories and files created by command line prompt, as demonstrated in the notebook above; 
 - a script, [weather.sh](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/blob/main/weather.sh), that contains commands that can be run when the script is executed in the command line;
 - the [requirements.txt](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/blob/main/requirements.txt) file, shows the libraries and packages installed on my machine to run Python code;
 - a Workflow, [.github/workflows/](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/tree/main/.github/workflows), that includes the [weather-data.yml](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/blob/main/.github/workflows/weather-data.yml) file that automates the script daily.
 - a [.gitignore](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/blob/main/.gitignore) as standard.

## Purpose of this project

The main objective of this work is:
- to know that there are many programs that use a [command-line interface](https://en.wikipedia.org/wiki/Command-line_interface) (CLI); 
- to get used to the command line environment, understand how it works and how powerful it can be;
- to perform tasks without a [graphical user interface](https://en.wikipedia.org/wiki/Graphical_user_interface), that is usually used over CLI;
- to use virtual machines accessible through a browser, and these provide [computing infrastructures](https://www.sciencedirect.com/topics/computer-science/computing-infrastructure) with useful tools;

These skills are especially valuable in the profession of a Data Analyst, because they expand the knowledge of the process within the computer and ease the manipulation of data in daily life.

## How to get started with the project

To get started with this work, please follow the installation instructions below. After that, the walkthrough in my notebook, [weather.ipynb](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/blob/main/weather.ipynb), explains how to execute the tasks through [GitHub Codespaces](https://docs.github.com/en/codespaces/overview). In the last part of my notebook, I explain my project, how I built the workflow and how I made it functional through [GitHub Actions](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions#overview).

## Installation

In order to complete the assessment for this module, the following programs are installed on the computer: 
- [Anaconda](https://www.anaconda.com/download), where Python is included;
- [Visual Studio Code](https://code.visualstudio.com/Download).

If the programs are not installed, [GitHub Codespaces](https://docs.github.com/en/codespaces/overview#benefits-of-github-codespaces) provides a virtual computer, with many programs included. All the tasks can be executed through here.

## Usage

The cloud GitHub Codespaces is the main tool to use the codes in the command line environment. These commands can be found in the notebook, [weather.ipynb](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/blob/main/weather.ipynb). The python code found in the notebook follows the [PEP 8](https://realpython.com/python-pep8/) coding style as standard.

Regarding the [workflow](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions#workflows), .github/workflows/, GitHub Actions automates with high efficiency the [script](https://docs.fileformat.com/programming/sh/#what-is-a-sh-file) weather.sh through [YAML file](https://docs.github.com/en/actions/writing-workflows/workflow-syntax-for-github-actions#about-yaml-syntax-for-workflows), [weather-data.yml](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/blob/main/.github/workflows/weather-data.yml). Even though this automation can be done through a physical computer, unfortunately this one needs to be on in order to be successfully completed. That's why it's easier to automate the jobs in a virtual computer made available by GitHub.

## Dependencies

The requirement.txt is essential regarding Python compatibility. This file was generated through the command line with the code `pip freeze > requirements.txt`, as instructed by [Microsoft Docs](https://github.com/MicrosoftDocs/visualstudio-docs/blob/main/docs/python/managing-required-packages-with-requirements-txt.md). In the future, if more packages are added, these can be listed manually in the file. To download the packages on any machine, use the code `pip install -r requirements.txt`. 
This file is very important because it will make my repository readable on other computers, specifying the libraries and the packages that are needed to run my notebook. Sometimes the Python version installed is different from computer to computer, so it's important to check the requirements.txt file, to run the code smoothly.

## Get help

If there's any problem with this project, please submit [issues](https://github.com/FatimaBOliveira/computer-infrastructure-assessment/issues) in this repository.

## Author

**by Fatima Oliveira** 

Email: g00438857@atu.ie or Fatima.21.00@hotmail.com