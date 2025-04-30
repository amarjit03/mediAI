# MediAI

MediAI is an innovative web application that leverages artificial intelligence to revolutionize the healthcare experience. By predicting diseases based on user-reported symptoms and connecting patients with the most suitable healthcare professionals, MediAI aims to make healthcare more accessible, efficient, and personalized. The platform also provides a secure system for managing medical records, enabling seamless sharing between patients and doctors through QR codes.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)


## Introduction

In today's healthcare landscape, patients often face challenges such as long wait times, misdiagnoses, and inefficient communication with healthcare providers. MediAI addresses these issues by offering:

- **Accurate Disease Predictions**: Users can input their symptoms, and the AI system predicts potential conditions with high accuracy.
- **Healthcare Recommendations**: The platform suggests healthcare professionals best suited to treat the predicted conditions.
- **Secure Medical Records Management**: Patients can upload, store, and share their medical records securely, ensuring privacy and accessibility.

MediAI empowers users to take control of their healthcare journey while providing healthcare professionals with tools to deliver better care.

## Features

- **Symptom Checker**: Users can input their symptoms, and the AI-driven system predicts potential diseases and suggests appropriate healthcare providers.
- **Medical Records Management**: Patients can upload their medical records to a secure database, accessible to doctors via a QR code scan.
- **Generative Chatbot**: An AI-powered chatbot is available to answer common questions about symptoms, diseases, and treatments, enhancing user engagement and providing immediate assistance.

## Technologies Used

- **Frontend**: Streamlit for an intuitive and user-friendly interface.
- **Backend**: Python and Flask for robust and scalable server-side logic.
- **Machine Learning**: Hugging Face Transformers and LangChain for advanced AI-driven predictions and natural language processing.
- **Database**: Secure storage solutions for managing sensitive medical records.
- **Deployment**: Hosted on Vercel for fast and reliable access.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Python](https://www.python.org/downloads/)
- [Node.js and npm](https://nodejs.org/)

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/amarjit03/mediAI.git
   cd mediAI
   ```

2. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   npm install
   ```

3. **Run the Application**:

   ```bash
   streamlit run app.py
   ```

## Usage

1. **Symptom Checker**: Navigate to the symptom checker page, input your symptoms, and receive predictions along with healthcare recommendations.
2. **Medical Records**: Upload your medical records securely and generate a QR code for easy sharing with healthcare providers.
3. **Chatbot**: Interact with the AI-powered chatbot for quick answers to your healthcare-related questions.

## Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


