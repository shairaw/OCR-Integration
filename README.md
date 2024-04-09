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
OCR free Document Understanding Transformer: <br/>
<img src="https://raw.githubusercontent.com/clovaai/donut/master/misc/overview.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
