# Document Extractor LLM

This project aims to extract relevant information from documents using Large Language Models (LLMs). The implementation leverages the power of LLMs to read, understand, and extract data from various documents, making it useful for a wide range of applications in data processing, automation, and information retrieval.

## Demo Video

You can find a small demonstration of the Streamlit app implementation of this project:  


https://github.com/user-attachments/assets/47506049-d56d-46b3-b3f9-efa65449c719


## Project Overview

The main goal of this project is to build an LLM-based document extraction tool. The tool allows users to input a variety of documents and have relevant information extracted and presented in a structured format. This project uses state-of-the-art language models, OpenAI, and Chroma for the vector database, as well as Retrieval-Augmented Generation (RAG) for context to process documents and extract the desired data.

## Features

- **Document Extraction**: Extracts structured data from documents using Large Language Models.
- **Streamlit Interface**: A user-friendly interface for extracting data from documents.
- **Dockerized Application**: The application is containerized using Docker for easy deployment and usage.

## Getting Started

1. **Install Docker**: First, ensure Docker is installed on your computer. You can download and install it from the official [Docker website](https://www.docker.com/).

2. **Pull the Docker Image**: Open your terminal and run this command to get the app:

   ```bash
   docker pull your_dockerhub_username/streamlit-app
   ```

3. **Run the App**: Start the app by running:

   ```bash
   docker run -p 8501:8501 your_dockerhub_username/streamlit-app
   ```

   This will launch the app on port `8501`.

4. **Open the App**: Open your web browser and go to [http://localhost:8501](http://localhost:8501).

5. **Stop the App**: To stop the app, press `Ctrl+C` in the terminal or use:

   ```bash
   docker stop <container_id>
   ```

   Replace `your_dockerhub_username` with the actual username you used to upload the Docker image.
