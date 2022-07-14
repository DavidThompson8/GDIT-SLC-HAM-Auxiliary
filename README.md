# GDIT-SLC-HAM-data-prep

Script for sorting the HAM10000 dataset for use in GDIT's Skin Lesion Classifier

## Setup

Ensure your computer has Python installed.
You will need a directory that contains the subdirectory 'HAM10000data'.

'HAM10000data' should have two subdirectories, 'train' and 'valiation'.

'train' and 'validation' should each contain the following subdirectories: 
- 'nv'
- 'mel'
- 'bkl'
- 'bcc'
- 'akiec'
- 'vasc'
- 'df

## Use
1. Download 'HAM_data_prep.ipynb'. Alternatively, copy and paste the code into a .py file.
2. Place the script in 'HAM10000data's parent directory.
3. Edit training and validation limit variables for each class to fit the sample size you wish to use. Values used for the real model are included as comments.
4. Run the script.

