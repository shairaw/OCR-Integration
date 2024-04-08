# OCR-free Data Extraction with Transformers

## Languages and Utilities Used

- Python
- DONUT
- Pix2Struck
- PyTorch
- End-to-end Product Development

## Environments Used

- macOS (Catalina)
- TensorFlow Version: 2.6

# Overview 
This project addresses the real case scenario of the automation of processing client information and documents for the company Roots Innovative Labs (GiBots), aiming to optimise document classification, error detection, data extraction, and validation.

# Methodology

The Donut architecture was adopted to address document classification and data extraction.

This model was proposed in OCR-free Document Understanding Transformer by Geewook Kim, Teakgyu Hong, Moonbin Yim, Jeongyeon Nam, Jinyoung Park, Jinyeong Yim, Wonseok Hwang, Sangdoo Yun, Dongyoon Han, Seunghyun Park. Donut consists of an image Transformer encoder and an autoregressive text Transformer decoder to perform document understanding tasks such as document image classification, form understanding and visual question answering.

<p align="center">
Launch the utility: <br/>
<img src="https://private-user-images.githubusercontent.com/73080100/271844050-015b1eb4-6679-480a-981d-74945d390b57.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTI1Njk2NDEsIm5iZiI6MTcxMjU2OTM0MSwicGF0aCI6Ii83MzA4MDEwMC8yNzE4NDQwNTAtMDE1YjFlYjQtNjY3OS00ODBhLTk4MWQtNzQ5NDVkMzkwYjU3LmpwZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MDglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDA4VDA5NDIyMVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTExNzYxY2Y3YmUxOWE0ZThmODVhYzM1NzhmN2U1YTQyMDM4NWFkNmVlYzEwZjc3NDQ3ZGVmNTE0NTIxMzYzMGYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.nTEvbfyGzPrqAda72ToZMGF8VEPusXlWaQST5mQxaWU" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

The Donut model will be fine-tuned to address the document classification problem. For the data extraction challenge, inference will be applied directly to a pre-trained Donut model

## Objectives

1. Reduction in response times and improvement in customer experience.
2. Research in the field of Visual Document Understanding (VDU).
3. End-to-end automation with high precision and efficiency.
4. Selection and adaptation of suitable AI models.
5. Evaluation of results and project viability.

## Program Walkthrough

1. Data Collection: Gathered dataset as a subset of the companys reciepts for training and evaluation purposes. These are not open source as they contain sensitive information about clients. 
2. Model Selection: Conducted a thorough assessment of transformer models, including DONUT and Pix2struck, to determine the most suitable model for data extraction tasks.
3. Model Optimisation: Optimized transformer models to enhance their functionality and improve accuracy.
4. Integration: Integrated the selected transformer model into the data extraction pipeline to streamline the process.
5. Evaluation: Evaluated the performance of the integrated model on test datasets to ensure effectiveness and accuracy.
6. Deployment: Deployed the finalised solution for production use within the company, to automate processes. 
