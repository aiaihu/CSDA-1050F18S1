# Capstone Project: 2018 Podcast Listeners Analysis

## Project Overview
* Podcasters reply on ads for their finance support but they have challenge to target the podcast listeners. The one major reason is podcast platforms can see listeners download the podcast episodes but are unable to get much information about the listeners as almost all podcasts are completely free and listeners don't need to put their information such as credit card or names.

* Audience Insights Inc, a media research consultancy pulling together teams of media, research and data professionals to meet just about any assignment facing clients. 

* This project was a volunteer project for Audience Insights Inc. This project analyze the podcasing listeners in Canada. In Canada, this is just 3rd year to analysis the podcasting data. I used The Canadian Podcast Listener 2018 Survey Data to focuse on below research questions but will not limite to these:

   - To what extent is income affecting people listening podcast?
   - To what extent are gender and age affecting people listening podcast?
   - To what extent are devices affecting listeners of podcasts? 
   - What are the popular 10 podcasts listed from the survery data?
   - How listeners react to the advertising in podcasts?

## Language: R

## Method: K-Modes Clustering for the segementation

## Libraries
library(data.table)
library(dplyr)
library(tidyr)
library(ggplot2)
library(stringr)
library(DT)
library(knitr)
library(grid)
library(gridExtra)
library(corrplot)
library(methods)
library(Matrix)
library(reshape2)
library(kableExtra)
library(cluster) # for gower similarity and pam
library(readr)
library(Rtsne) # for t-SNE plot

Here you will outline your entire project. Detail the purpose, background on the project, and contents found here. 

  - This should include how to install dependecies and run the project from start to finish
  - Use proper formatting here - make it look pretty
  - Magic, not how I want to see the results appear

# Updates Limitations Requirements?

  - If you have data here - put it in it's own data folder. If it's downloadable link to it. 
  - Don't post passwords, usernames, or private information here.


You can also:
  - Link files from GitHub, Dropbox, Google Drive and One Drive..the web etc. 
  - Be creative and look around GitHub for great "Readme.md" examples. 
 
* [Google] - its your friend for Markdown editors and syntax


### Installation

Often these have explicit directions per platform. If you're using anaconda/python make sure to list the versions/libraies. 
e.g., Install the dependencies and devDependencies and start the server.

```sh
$ cd data
$ npm install -d
$ node app
```

For production environments...

```
conda install -c conda-forge tensorflow-gpu
pip install pandas
etc. etc. 
```
