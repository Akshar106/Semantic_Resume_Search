# Semantic Resume Search Web App

## Project Description

The Semantic Resume Search Web App is designed to allow users to search for relevant resumes based on specific criteria, such as job title and years of experience. The application uses a semantic search approach, leveraging Sentence Transformers to understand the content of resumes and provide accurate search results. The web app is built using Streamlit for an interactive user interface.

## Features

- **Semantic Search**: Search for resumes based on job titles, experience levels, and specific skills.
- **User-Friendly Interface**: Easy-to-use search bar and filters.
- **Upload Functionality**: Users can upload new resumes to update the database.
- **Responsive Design**: Optimized for various devices.

## Technologies Used

- **Streamlit**: For web app development.
- **Sentence Transformers**: For semantic search and model training.
- **Python**: For scripting and backend logic.


## Setup Instructions

### Prerequisites

- Python 3.7+
- Pip (Python package installer)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/semantic-resume-search.git
   cd semantic-resume-search

2. **Install dependencies::**
   ```bash
   pip install -r requirements.txt

3. **Download and prepare resume data:**

   -Place your resume PDFs in the data folder.

4. **Train the model:**
   ```bash
   python train_model.py

5. **Run the web app:**
   ```bash
   streamlit run app.py

## Usage

1. **Search Resumes:**

   - Open the web app in your browser.
   - Use the search bar to enter job titles and experience levels (e.g., "Data Scientist + 2 years experience").
   - View the relevant resumes listed based on your search criteria.

2. **Upload New Resumes:**

   - Use the upload functionality to add new resumes to the database.
   - The new resumes will be included in future searches.
  
## Weekly Report

### Week 1 : Project Setup and Initial Development

#### Day 1-2: Project Initialization and Setup

- Set up the project repository on GitHub.
- Created a README file with a project description, objectives, and setup instructions.
- Organized the project structure with folders for app.py, train_model.py, and a data folder for resumes.

#### Day 3-4: Data Collection and Preprocessing

- Collected and organized sample resumes in the data folder.
- Wrote a script to preprocess the resumes, extracting text from PDFs and storing it in a structured format.

#### Day 5-7: Model Training Preparation

- Explored the Sentence Transformers library and chose an appropriate pre-trained model (all-MiniLM-L6-v2).
- Prepared the training dataset by creating labeled examples from the resume data, focusing on job titles and years of experience.

### Deliverables: 

- Initialized project repository with a README file.
- Collected and preprocessed sample resumes.
- Prepared the training dataset for the model.
