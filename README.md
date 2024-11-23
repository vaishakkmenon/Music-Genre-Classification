# Music-Genre-Classification

CS667 Machine Learning Final Project - Music Genre Classification using the GTZAN Dataset and other supplemental data

Dataset was downloaded from https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification?resource=download-directory

Download the zip file and extract all files to the folder you are working in
Gitignore will automatically ignore the Folder and the Zip file that you

We will need to have the same folder structure so that the gitignore will match for everybody.
I created a subdirectory for GTZAN because this is the initial dataset with 1000 songs, we will add more later which we can create subdirectories for. Just trying to create some organization intially.

My Current Structure (Vaishak):

- Music-Genre-Classification
  - Data
    - GTZAN
      - genres_original
      - images_original
        - features_3_sec.csv
        - features_30_sec.csv
  - .gitignore
  - Models
    - CNN
    - KNN
    - Random_Forest
    - SVM
  - base_env
  - Data.zip
  - Project_Proposal.pdf
  - README.md

I work in VSCode, and with their support for jupyter notebook, it is easy to select a kernel. We can work together to figure it out for each other if need be.

Conda Environment Setup:

Install Conda if not installed already
Move to directory with environment.yaml
Run following commands

- conda env create -f environment.yaml
- conda activate 667-MGC
- conda list (OPTIONAL; Just a check to see the environment is installed)
- conda deactivate (Method to deactivate the environment)
