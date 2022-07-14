# GDIT-SLC-HAM-data-prep

Script for sorting the HAM10000 dataset for use in GDIT's Skin Lesion Classifier

## Prerequisites 

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
3. Place the script in 'HAM10000data's parent directory.
4. Edit training and validation limit variables for each class to fit the sample size you wish to use. Values used for the real model are included as comments.
5. Access the HAM10000 data: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T
6. Download HAM10000_images_part_1.zip, HAM10000_images_part_2.zip, and HAM10000_metadata.tab
7. Make sure the metadata file is saved as 'HAM10000_metadata.csv', and place it in the same directory as the script.
8. Extract the contents of the two .zip folders into 'HAM10000data'.
9. Run the script.

