# Data-Engineering-Project
A Data engineering project to curate a Speech-To-Text dataset.

# Setup Instructions
1.Clone this repository.
2.You can use jupyter notebook or Google Colab to run the ipynb file.
3.Install all the required packages present in ipynb file.
4.Ensure that you have a stable internet connection.


# How to run the scripts
1.Open the ipynb file in your jupyter notebook or Google Colab.
2.To run the AI4Bharat_audio.ipynb file you just trigger run.
3.To run the AI4Bharat_transcript.ipynb file you need to provide the course url as input and pass the path to save the file.
4.Also path to load the same file and perform pre-processing.
5.Once the script is finished, you can view the processed transcript in .txt format.


# Observations
1.The AI4Bharat_transcript.ipynb code automates the downloading of a transcript from a website, extracts the unique identifier of a Google Drive file.
2.It scrapes the text content of the PDF file and save it directly as a text file.
3.It also removes the first 5 lines of the transcript file, converts all text to lowercase, removes punctuation, and converts numbers to words.
4.The AI4Bharat_audio.ipynb file take input of video file and process it into wav format.
