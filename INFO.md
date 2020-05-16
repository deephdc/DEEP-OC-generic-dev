<div align="center">
<img src="https://marketplace.deep-hybrid-datacloud.eu/images/logo-deep.png" alt="logo" width="300"/>
</div>

# Welcome to DEEP Developement Environment

**Project:** This work is part of the [DEEP Hybrid-DataCloud](https://deep-hybrid-datacloud.eu/) project that has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 777435.

DEEP Development Environment (DDE) aims to facilitate the integration of your code with DEEP solutions, development and testing it directly in the cloud environment.

## Table of Content

* [Introduction](#Introduction)
* [Configure git for commits](#Configure-git-for-commits)
* [DEEP Documentation](#DEEP-Documentation)
* [DEEP Tools](#DEEP-Tools)
* [Acknowledgments](#Acknowledgments)


## Introduction
DEEP Development Environment uses as a base a Docker Image of either 
* [TensorFlow](https://tensorflow.org) framework (1.14.0 | 1.15.0 | 2.0.0)
* [PyTorch](https://pytorch.org/) (1.2 | 1.4)
* or Ubuntu 18.04

It leverages 
* [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/index.html) web-based user interface for developing and debugging your code

Includes: 
* [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/) template tool to start or integrate your project with DEEP solutions profiting from [DEEP Data Science template](https://github.com/indigo-dc/cookiecutter-data-science)

Contains DEEP components:
* [DEEP as a Service API](https://docs.deep-hybrid-datacloud.eu/projects/deepaas/en/latest/) is REST API that provids access to machine learning models
* [flaat](https://github.com/indigo-dc/flaat)
* [oidc-agent](https://github.com/indigo-dc/oidc-agent)

Python related packages:
* python
* python-dev
* pip

And a number of tools to facilitate the development:
* git
* curl
* [mc](https://midnight-commander.org/) : Midnight Commander, a visual file manager
* openssh-client
* [rclone](https://rclone.org) : a command line program to sync files and directories to and from cloud storages
* wget

## Configure git for commits

Using pre-installed `git` you can easily clone projects in DDE. If you want to commit your changes back, you have to configure global `user.name` and `user.email` as follows: 

```bash
$ git config --global user.name "Your Name"
$ git config --global user.email "your_email_for_git_account@domain.zone"
```

## DEEP Documentation



## DEEP Tools

## Acknowledgements

Please consider citing the DEEP Hybrid DataCloud project:

> García, Álvaro López, et al. [A Cloud-Based Framework for Machine Learning Workloads and Applications.](https://ieeexplore.ieee.org/abstract/document/8950411/authors) IEEE Access 8 (2020): 18681-18692. 