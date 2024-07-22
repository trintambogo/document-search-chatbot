# A Document search chatbot

## Introduction

The Document Search Chatbot is designed to help users find specific information within a document. It uses AWS services like S3 for storage and other tools for searching and retrieving the relevant information.

## Features

- Upload documents to an S3 bucket
- Use pretrained model in amazon bedrock
- Search and retrieve answers from the uploaded documents
- User-friendly interface

## Architecture

### Prerequisites

### Step-by-Step Guide

1. **Create an S3 Bucket**

   - Log in to your AWS Management Console.
   - Navigate to the S3 service.
   - Click on "Create bucket."
   - Enter a unique name for your bucket and select the appropriate region.
   - Click "Create bucket."
     

2. **Upload Documents**

   - Go to your S3 bucket.
   - Click on "Upload."
   - Select the document(s) you want to upload.
   - Click "Upload" to finish.
  
     ![image](https://github.com/user-attachments/assets/10a8e7e3-ba5a-44f4-ba6c-94fddad6cec6)

3. **Setting Up Amazon Bedrock Knowledge Base**
   - Click on Get started
   - On the left side, click on "Knowledge Bases" and then click on "Create a knowledge base." This is where the model will retrieve information and answers.
   - Enter an appropriate name for your knowledge base.
   - For IAM permsiions, select "Create and use a new service role."
   - For the data source, choose "Amazon S3"
   - Leave everything as default and Click "Next"
   - Enter a data source name.
   - Click "Browse S3" and select the buckt where you have uploaded your files.
   - ![image](https://github.com/user-attachments/assets/0aae7d7d-f871-4940-93a4-8fd030f0e0f9)
   - Click "Next"
   - On the embeddings model, select Titan embeddings G1 - Text v1.2
     ![image](https://github.com/user-attachments/assets/9c159154-8f0c-4618-ab4e-4c745a9b773d)
   - On the vector database, select create a new vector store
     ![image](https://github.com/user-attachments/assets/348bb891-77d2-4f54-ab0c-9d247f87b851)
   - Review everything and click on create knowledge base
     ![image](https://github.com/user-attachments/assets/3b409eab-0365-40a1-90c4-5e4fec0ba028)



  


