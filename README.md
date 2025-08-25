# Intelligent-Data-Extraction-and-Summarization-Agent
1. Overview
This project demonstrates an end-to-end prototype for natural language processing (NLP) on Google Cloud Platform (GCP). It uses native GCP services to ingest, process, and analyze unstructured text data, culminating in a summarized report.

2. Architecture
The workflow is architected on the following GCP services:

BigQuery: For scalable data storage and querying of the unstructured text dataset.

Google Cloud Natural Language API: For pre-trained models to perform sentiment analysis and entity extraction.

Vertex AI: To leverage the powerful Gemini model for text summarization.

Jupyter Notebook (Vertex AI Workbench): The primary development environment for running the Python code.

3. Setup and Prerequisites
To run this project, you need:

A Google Cloud project with billing enabled.

The following APIs enabled:

BigQuery API

Cloud Natural Language API

Vertex AI API

A service account with the appropriate roles (BigQuery Data Viewer, Vertex AI User, Cloud Natural Language API User) and its key file downloaded. The GOOGLE_APPLICATION_CREDENTIALS environment variable should be set to the path of this key file.

4. Dataset
The project uses the Consumer Financial Protection Bureau (CFPB) Complaints Database, a public dataset hosted on BigQuery.

5. How to Run

Set up your GCP project and enable the necessary APIs.

Clone this repository.

Install the required dependencies using the provided requirements.txt file.

Open the Jupyter notebook (your_notebook_name.ipynb) in Vertex AI Workbench.

Update the PROJECT_ID variable in the notebook with your GCP Project ID.

Run the notebook cells sequentially.
