# ASX_Announcements_NLP_CNN
NLP Models built on ASX announcements

0_pdfScraper_and_Cleaner.ipynb - downloads and cleans ASX announcement pdfs

1_1D_CNN.ipynb - 1 dimensional CNN to predict if share price went up, down, or stayed flat

2_2D_CNN.ipynb - 2 dimensional CNN to predict if share price went up, down, or stayed flat

3_LogisticRegression.ipynb - Logistic regression classifier to predict if announcement is market sensitive



-----------------------
To run this code:
Open 0_pdfScraper_and_Cleaner, install packages, and update folder references to your own local directories.

PDFs will download from target website and save to the selected folder. This process is slow but can be paused/stopped and resumed without losing progress.

Download the CSVs containing daily ASX snapshots from the website specified in the program. These need to be downloaded and saved manually for the selected time period.

Store the individual dates as a list prior to the import step.

Run the rest of the program.

From here, any/all of the subsequent models (1, 2,and 3) can be run and in any order as they are all independent of each other.
