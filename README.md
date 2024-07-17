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

### Week 2: Model Training and Web App Development

#### Day 8-10: Model Training

- Trained the Sentence Transformer model using the prepared dataset.
- Saved the trained model for later use in the web app.

#### Day 11-12: Initial Web App Setup

- Set up the Streamlit web app framework in app.py.
- Created a basic interface with a search bar and a display area for results.

#### Day 13-14: Integrate Model with Web App

- Loaded the trained model in the web app.
- Implemented search functionality to query the model and display relevant resumes based on user input.

### Deliverables:

- Trained Sentence Transformer model.
- Initial version of the Streamlit web app with basic search functionality.

### Week 3: Feature Enhancement and Testing

#### Day 15-17: Feature Enhancement

- Improved the search functionality with additional filters such as experience level and specific skills.
- Added functionality to allow users to upload new resumes and update the database.

#### Day 18-19: User Interface and Experience

- Enhanced the web app UI for better user experience, including layout adjustments and styling.
- Implemented error handling and edge case management to ensure robust performance.

#### Day 20-21: Testing and Debugging

- Performed thorough testing of the web app, including unit tests for individual components and end-to-end testing of the user flow.
- Fixed bugs and improved performance based on test results.

### Deliverables:

- Enhanced search functionality with additional filters.
- Improved UI/UX for the web app.
- Debugged and tested web app.

### Week 4: Finalization and Documentation

#### Day 22-24: Final Touches

- Conducted final optimizations for the model and web app, focusing on speed and accuracy.
- Ensured the web app is responsive and works well on different devices.

#### Day 25-26: Documentation

- Documented the code and functionalities in detail.
- Created user manuals and guides for the web app, explaining how to use the search functionality and upload new resumes.

#### Day 27-28: Deployment Preparation

- Prepared the web app for deployment, setting up a server and configuring the environment.
- Tested the deployment process to ensure smooth operation.

#### Day 29-30: Deployment and Final Review

- Deployed the web app to a cloud platform (e.g., AWS or Heroku).
- Conducted a final review and gathered feedback from a few users to identify any last-minute improvements.

### Deliverables:

- Finalized and optimized web app.
- Comprehensive project documentation.
- Deployed web app accessible to users.

## Final WebApp: 
![Screenshot 2024-07-17 214325](https://github.com/user-attachments/assets/69df780b-7e19-4574-a6b1-ea25bac014d6)
![Screenshot 2024-07-17 214421](https://github.com/user-attachments/assets/cdd00d83-4b65-40fe-959f-7516b63b59fa)
![Screenshot 2024-07-17 214439](https://github.com/user-attachments/assets/a9a646f2-a5cd-4247-9faf-74719b410e6d)
![Screenshot 2024-07-17 214518](https://github.com/user-attachments/assets/74d3136d-1849-4584-839b-56d19db0db44)
![Screenshot 2024-07-17 214539](https://github.com/user-attachments/assets/51a6fb53-5aa0-4752-ba91-3573dd662fad)


## Contact: 

- Email:  patelakshar1107@gmail.com.
- LinkedIn: https://www.linkedin.com/in/akshar-patel-6b03b71ba/
