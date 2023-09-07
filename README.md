# IDS-706-Proj1
A hands on Project to start with GitHub repository
#By - Ayush Gupta
#Net ID- ag758

## Goal
The project goal is to get used to working on GitHub and create a basic working repository that could be used in future for other projects. Hence, it has been kept very basic and only goal is to install packages. 

## Developing
We have created the following files  in the project : 
1. Makefile
2. README.md
3. requirements.txt
4. Github Actions
5. .devcontainer
6. A python file

The Makefile.md has two targets along with the associated commands:
1. install
2. test

requirements.txt contains all the packages that need to be installed. 


The GitHub Actions workflow is writtened in YAML formatt that automates various tasks in GitHub repositories with the name defined as Ayush_CI.

#WorkFlow :
The GitHub actions 'Make install' call the install function in MakeFile to install all the packages there are in requirements.txt (mentioned under Makefile install )

The following project was run via Actions Tab and all the mentioned actions had been successfully executed. 



[![Ayush CI](https://github.com/ayushg245/IDS-706-Proj1/actions/workflows/cicd.yml/badge.svg)](https://github.com/ayushg245/IDS-706-Proj1/actions/workflows/cicd.yml)

