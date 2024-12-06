# AI-POWERED JOB RECOMMENDATION SYSTEM WITH NLP AND FLASK INTEGRATION

## About
A cutting-edge platform leveraging Machine Learning (ML) and Natural Language Processing (NLP) to deliver personalized job recommendations based on user skills and job descriptions. The system accelerates the job search process and enhances job matching accuracy, making it easier for users to find roles suited to their expertise.

## Description
This project utilizes advanced ML and NLP techniques to analyze user skills and match them with relevant job opportunities based on skill similarity. It features an intuitive user interface built with Flask, ensuring seamless interaction for users.

## Table of Contents
1. [Features](#features)
2. [Tools and Technologies Used](#tools-and-technologies-used)
3. [Configuration and Installation](#configuration-and-installation)
4. [Usage Instructions](#usage-instructions)
5. [Future Scope](#future-scope)
6. [Known Issues](#known-issues)
7. [Contact](#contact)

## Features
- **Skill Analysis**: Extracts and analyzes user skills based on job descriptions.
- **Skill Similarity Calculation**: Matches users with the most relevant job offers.
- **User Interface**: Simplified and efficient interaction via a Flask web application.

## Tools and Technologies Used
- **Programming Language**: Python
- **Web Framework**: Flask
- **Data Storage**: MongoDB
- **Libraries**:
  - **BeautifulSoup**: For web scraping and data extraction.
  - **Spacy**: For advanced NLP tasks.
  - **Scikit-learn**: For model training and evaluation.
  - **Matplotlib**: For visualizing data insights.
- **Data Formats**: JSON

## Configuration and Installation

### Prerequisites
    - Ensure Python is installed.
    - Install dependencies by running
       -```pip install -r requirements.txt```
### Database Configuration
    - Set MongoDB connection parameters in the config.py file.
### Model Training
    - Execute the model training script
       -```python training.py```
### Web Application Launch
    - Start the Flask web application
       -```python app.py```

## Usage Instructions
- Open the application in your browser after running the Flask server.
- Upload or input your skills and job descriptions.
- View the recommended job roles based on skill similarity analysis.
  
## Future Scope
- **Improved Recommendation Models**: Incorporate deep learning techniques for enhanced accuracy.
- **Expanded Data Sources**: Integrate multiple job portals for a wider dataset.
- **User Account Management**: Enable user profiles for saving preferences and tracking applications.
  
## Known Issues
- Limited support for non-English job descriptions.
- Dependency on accurate skill extraction from job descriptions.
  
## Contact
- For questions, issues, or contributions, reach out via GitHub Issues or contact:
   - **Name**: Preethi.A
   - **Email**: preethi522002@gmail.com
   - **LinkedIn**: https://www.linkedin.com/in/preethi522/
