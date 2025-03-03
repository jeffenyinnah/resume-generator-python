# Resume Generator

This project is a **Resume Generator** built using Streamlit, OpenAI, and Python. It allows users to create professional resumes by filling out a form, and the content is generated using OpenAI's GPT-4 model. The resumes can be downloaded in Word format (`docx`) and are styled according to predefined templates.

## Features

- **User Authentication**: Users can sign up and log in to track their resume generation history.
- **Resume Generation**: Users can input personal, professional, and educational details to generate a resume.
- **Template Support**: The application supports multiple resume templates, and users can choose the one they prefer.
- **Download in Word Format**: Generated resumes can be downloaded as `.docx` files.
- **OpenAI Integration**: The resume content is generated using OpenAI's GPT-4 model for professional and concise content.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.8 or higher
- [Poetry](https://python-poetry.org/) (for dependency management)
- MongoDB Atlas (for user data storage)
- OpenAI API key

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/resume-generator.git
   cd resume-generator

2. **Set up environment variables**
   ```bash
   OPENAI_API_KEY=your_openai_api_key
   MONGO_URI=your_mongodb_atlas_uri

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt

4. **Run the application:**
   ```bash
   streamlit run resume-generator.py

5. **Access the application:**
   Open your browser and navigate to http://localhost:8501

## Usage
#### Sign Up/Log In:
- New users can sign up by providing an email and password.
- Existing users can log in using their credentials.

#### Fill Out the Form:
- Provide personal information (name, phone, LinkedIn, etc.).
- Add professional details (industry, job type, work experience, etc.).
- Include educational background and skills.

#### Generate Resume:
- Click the "Gerar Currículo" button to generate the resume.
- The resume content will be displayed, and you can download it as a Word document.

#### Template Selection:
- Choose from available templates to style your resume.

   
