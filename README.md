# BioASQ QA System

## Prerequisites

### Question Processing
1. Download all the files at the following link which contains the pre-train model for question type classification:

   https://drive.google.com/drive/folders/1w6J29UCf5jI86FrMpcZdW9NlWcrPsO91?usp=sharing

2. In your Google Drive make a folder called **Colab Notebooks**

3. Inside Colab Notebooks folder, make a folder called **BioASQ**

4. Inside of BioASQ folder, make a folder called **Model**

5. Upload files from step 1 into **Model** folder

6. Download **input.csv**  from the following link:

   https://drive.google.com/file/d/1ZqAqo6Mg571UBB0aHPGuFdG4c2Lh_oPd/view?usp=sharing
   
7. Download **qp_demo.xml** from the following link:

   https://drive.google.com/file/d/1O_PMC51F5GvuC1R6r9QUFxQFkqJqQAqE/view?usp=sharing
   
8. Upload **input.csv** & **qp_demo.xml** files into your **Colab Notebooks/BioASQ** Google Drive folder


### Information Retrieval
1. Download the PubMed dataset from the following link (**Warning** the folder is over 8 GB)

   https://drive.google.com/drive/folders/1VmA9b4uyLMpH4v0wlADL2l9N9Wa5WzX3?usp=sharing

2. Upload the **data2** folder into your **Colab Notebooks/BioASQ** Google Drive folder


## How to use
1. In this repository, click on **BioASQ_QA_System.ipynb**

2. Click the **Open in Colab** button

3. In Colab, go to **Runtime** -> **Run all**

4. There may be a warning that "This notebook was not authorized by Google" since the notebook comes from GitHub and wants to access files from Google Drive: click **RUN ANYWAY**

5. In the first cell make sure you click the URL and choose the Google account that has the files you uploaded from the Prerequisite section

6. Sometimes the square, copy button will cause problems so it is recommended to copy the code manually and paste it back into Colab


## Where results are stored
The results are stored in the **qp_demo.xml** file in your **Colab Notebooks/BioASQ** Google Drive folder


## TODOs
1. Figure out why system doesn't work when using an already indexed folder from Google Drive
