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

### Installation

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

