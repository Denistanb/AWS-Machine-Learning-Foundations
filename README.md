# AWS Machine Learning Foundations – Learning Journey  

This repository contains all my hands-on work and notes from the **AWS Machine Learning Foundations** course offered by **AWS Academy**. The course is designed to teach the **end-to-end machine learning lifecycle**, using real AWS tools like **Amazon SageMaker**, **Rekognition**, **Forecast**, and **Comprehend**.

If you're exploring how **machine learning works in the cloud**, or want to understand how to build and deploy ML models using AWS services — this repo is for you.

## What I Learned

### Machine Learning Fundamentals
- What is Machine Learning?
- Real-world business problems solved by ML
- Overview of ML process and tools
- Common ML challenges
- Demo: Introduction to **Amazon SageMaker**

### Working with Data
- Formulating ML problems from business goals
- Data collection, transformation (ETL), and security
- Exploring and evaluating data
- Feature engineering (cleaning, encoding, handling outliers)
- Labs:
  - Create & import data in SageMaker
  - Explore datasets
  - Encode categorical features

---

### Model Building and Evaluation
- Training models with SageMaker
- Hosting and deploying trained models
- Evaluating model performance (accuracy, precision, recall)
- Classification metrics and threshold tuning
- Hyperparameter tuning using SageMaker and Autopilot
- Labs & Demos:
  - Model training & deployment
  - Generating performance metrics
  - Hyperparameter tuning

### Forecasting with Time Series Data
- Time series fundamentals and preprocessing
- Using **Amazon Forecast** for automated time series predictions
- Simulation: Build forecasts with SageMaker Canvas

### Computer Vision
- Image and video analysis using AWS tools
- Face recognition and labeling using **Amazon Rekognition**
- Building custom datasets for training & testing
- Data labeling with **Amazon Ground Truth**

### Natural Language Processing (NLP)
- Basics of NLP and common use cases
- Using **Amazon Comprehend**, **Polly**, and **Translate**
- Hands-on demos with managed NLP services

### Generative AI with AWS
- What is Generative AI?
- Prompt engineering basics
- Exploring **Foundation Models (FMs)** in AWS
- Using **Amazon Q Developer** to create ML models with code

## Tools & Technologies Used
- Amazon SageMaker
- Amazon Forecast
- Amazon Rekognition
- Amazon Comprehend, Polly, Translate
- SageMaker Canvas & Ground Truth
- Amazon Q Developer

## Getting Started

Follow these instructions to get a copy of this project up and running on your local machine and AWS environment.

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- An AWS account with permissions for SageMaker, S3, and Lambda
- AWS CLI configured on your machine

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Denistanb/AWS-Machine-Learning-Foundations.git
   cd AWS-Machine-Learning-Foundations
   ```

2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure AWS CLI:**
   ```bash
   aws configure
   ```

### Usage

- Open Jupyter Notebook:
  ```bash
  jupyter notebook
  ```
- Navigate to the desired notebook and follow the instructions for each module.
- To run SageMaker jobs or interact with AWS services, ensure your AWS credentials are properly configured.

## Project Structure

```
AWS-Machine-Learning-Foundations/
├── 05-facedetection.ipynb           # Face detection (Computer Vision)
├── 3_2-machinelearning.ipynb        # ML fundamentals/data prep
├── 3_3-machinelearning.ipynb        # Categorical encoding lab
├── 3_4-machinelearning.ipynb        # Data split & XGBoost training
├── 3_5-machinelearning.ipynb        # Model deployment/batch transform
├── 3_6-machinelearning.ipynb        # Model evaluation/metrics
├── 3_7-machinelearning.ipynb        # Hyperparameter tuning
├── Flight_Delay-Student.ipynb       # Time series/forecasting lab
├── Lab 6/                           # Chatbot in website
└── Vertebral Column.ipynb           # Classic dataset classification
```

- **data/**: Contains datasets used for training and evaluation.
- **notebooks/**: Step-by-step guides and hands-on experiments.
- **src/**: Source code, functions, and classes for ML models and utilities.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request describing your changes

## Contact

For questions and feedback, please open an issue or contact the maintainer:

- GitHub: [Denistanb](https://github.com/Denistanb)
- Email: denistanb@gmail.com

---
