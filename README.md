# MediAI

MediAI is a web application that leverages artificial intelligence to predict diseases based on user-reported symptoms and connects patients with the most suitable healthcare professionals. The platform also allows users to upload and manage their medical records, which can be accessed by doctors through a secure QR code system.

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
- [Contact](#contact)

## Introduction

In the current healthcare landscape, patients often face challenges such as long wait times, misdiagnoses, and inefficient communication with healthcare providers. MediAI aims to address these issues by providing:

- Accurate disease predictions based on user-inputted symptoms.
- Recommendations for healthcare professionals best suited to treat the predicted conditions.
- A secure platform for storing and sharing medical records between patients and doctors.

## Features

- **Symptom Checker**: Users can input their symptoms, and the AI-driven system predicts potential diseases and suggests appropriate healthcare providers.
- **Medical Records Management**: Patients can upload their medical records to a secure database, accessible to doctors via a QR code scan.
- **Generative Chatbot**: An AI-powered chatbot is available to answer common questions about symptoms, diseases, and treatments, enhancing user engagement and providing immediate assistance.

## Technologies Used

- **Frontend**: Streamlit
- **Backend**: Python, Flask
- **Machine Learning**: Hugging Face Transformers, LangChain
- **Database**: Secure storage solutions for medical records
- **Deployment**: Hosted on Vercel

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
